# Bandit Level 5 → 6

## Goal
Find the only human-readable file in inhere.

## Solution path

```bash
find inhere -type f -exec file {} + | grep -i text
```

## What I learned
Using find and file to identify content type.

## Note
This file intentionally does not contain passwords. Use the live OverTheWire challenge to obtain them.
