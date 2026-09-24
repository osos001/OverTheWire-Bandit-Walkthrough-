# Bandit Level 26 → 27

## Goal
Use the escaped shell and setuid binary to read bandit27's password.

## Solution path

```bash
./bandit27-do cat /etc/bandit_pass/bandit27
```

## What I learned
Combining shell escape with setuid execution.

## Note
This file intentionally does not contain passwords. Use the live OverTheWire challenge to obtain them.
