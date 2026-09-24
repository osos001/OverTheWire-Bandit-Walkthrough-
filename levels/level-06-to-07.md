# Bandit Level 6 → 7

## Goal
Find the file owned by bandit7, group bandit6, and 33 bytes in size.

## Solution path

```bash
find / -user bandit7 -group bandit6 -size 33c 2>/dev/null
```

## What I learned
Combining find predicates and suppressing permission errors.

## Note
This file intentionally does not contain passwords. Use the live OverTheWire challenge to obtain them.
