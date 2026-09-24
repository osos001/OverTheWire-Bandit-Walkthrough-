# Bandit Level 31 → 32

## Goal
Create the required file, commit it, and push it to the training repository.

## Solution path

```bash
git clone ssh://bandit31-git@bandit.labs.overthewire.org:2220/home/bandit31-git/repo
cd repo
echo 'May I come in?' > key.txt
git add key.txt
git commit -m 'Add key file'
git push
```

## What I learned
Git add/commit/push workflow and repository-side validation.

## Note
This file intentionally does not contain passwords. Use the live OverTheWire challenge to obtain them.
