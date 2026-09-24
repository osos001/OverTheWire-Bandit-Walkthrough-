# Bandit Level 19 → 20

## Goal
Use the setuid binary in the home directory to read bandit20's password.

## Solution path

```bash
./bandit20-do cat /etc/bandit_pass/bandit20
```

## What I learned
Understanding setuid privilege boundaries.

## Note
This file intentionally does not contain passwords. Use the live OverTheWire challenge to obtain them.
