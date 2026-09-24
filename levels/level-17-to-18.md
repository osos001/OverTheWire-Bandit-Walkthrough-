# Bandit Level 17 → 18

## Goal
Compare passwords.new and passwords.old to find the changed line.

## Solution path

```bash
diff -u passwords.old passwords.new
```

## What I learned
Using diff to isolate a single change.

## Note
This file intentionally does not contain passwords. Use the live OverTheWire challenge to obtain them.
