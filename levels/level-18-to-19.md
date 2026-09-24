# Bandit Level 18 → 19

## Goal
Read readme even though the SSH session is immediately logged out by .bashrc.

## Solution path

```bash
ssh -p 2220 bandit18@bandit.labs.overthewire.org cat readme
```

## What I learned
Executing a remote command without starting the interactive shell.

## Note
This file intentionally does not contain passwords. Use the live OverTheWire challenge to obtain them.
