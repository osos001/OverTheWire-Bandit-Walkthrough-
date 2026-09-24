# Bandit Level 9 → 10

## Goal
Extract the human-readable string preceded by several '=' characters.

## Solution path

```bash
strings data.txt | grep '='
```

## What I learned
Extracting printable strings from binary-like data.

## Note
This file intentionally does not contain passwords. Use the live OverTheWire challenge to obtain them.
