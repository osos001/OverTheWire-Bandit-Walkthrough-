# Bandit Level 20 → 21

## Goal
Use the setuid client to retrieve the next password from a local service.

## Solution path

```bash
echo '<current-password>' | nc -l -p 1234 & ./suconnect 1234
```

## What I learned
Local listener + setuid client; the client checks the supplied password.

## Note
This file intentionally does not contain passwords. Use the live OverTheWire challenge to obtain them.
