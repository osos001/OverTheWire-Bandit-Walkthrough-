# Bandit Level 13 → 14

## Goal
Use the provided SSH private key to access bandit14.

## Solution path

```bash
ssh -i sshkey.private bandit14@localhost -p 2220
```

## What I learned
SSH private-key authentication.

## Note
This file intentionally does not contain passwords. Use the live OverTheWire challenge to obtain them.
