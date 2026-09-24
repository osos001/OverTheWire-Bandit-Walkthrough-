# Bandit Level 15 → 16

## Goal
Submit the current password to localhost port 30001 over SSL/TLS.

## Solution path

```bash
openssl s_client -connect localhost:30001 -quiet
```

## What I learned
Using TLS from the command line.

## Note
This file intentionally does not contain passwords. Use the live OverTheWire challenge to obtain them.
