# Bandit Level 16 → 17

## Goal
Find the listening service in ports 31000-32000 and identify the one using SSL/TLS.

## Solution path

```bash
nmap -sV -p 31000-32000 localhost
openssl s_client -connect localhost:<SSL_PORT> -quiet
```

## What I learned
Port discovery plus service/TLS identification.

## Note
This file intentionally does not contain passwords. Use the live OverTheWire challenge to obtain them.
