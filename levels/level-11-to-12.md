# Bandit Level 11 → 12

## Goal
Decode text where letters are rotated by 13 positions.

## Solution path

```bash
tr 'A-Za-z' 'N-ZA-Mn-za-m' < data.txt
```

## What I learned
ROT13 using tr.

## Note
This file intentionally does not contain passwords. Use the live OverTheWire challenge to obtain them.
