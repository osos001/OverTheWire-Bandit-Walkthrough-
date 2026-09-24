# Bandit Level 21 → 22

## Goal
Inspect the cron job and script that periodically writes a password into /tmp.

## Solution path

```bash
cat /etc/cron.d/cronjob_bandit22
cat /usr/bin/cronjob_bandit22.sh
md5sum <<< 'I am user bandit22'
```

## What I learned
Cron inspection and tracing a scheduled script.

## Note
This file intentionally does not contain passwords. Use the live OverTheWire challenge to obtain them.
