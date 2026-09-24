# Bandit Level 8 → 9

## Goal
Find the only line in data.txt that occurs once.

## Solution path

```bash
sort data.txt | uniq -u
```

## What I learned
Sorting before using uniq.

## Note
This file intentionally does not contain passwords. Use the live OverTheWire challenge to obtain them.
