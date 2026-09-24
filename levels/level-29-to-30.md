# Bandit Level 29 → 30

## Goal
Inspect branches/history to find information not present in the default branch.

## Solution path

```bash
git clone ssh://bandit29-git@bandit.labs.overthewire.org:2220/home/bandit29-git/repo
cd repo
git branch -a
git log --all -p
```

## What I learned
Enumerating branches and inspecting all Git history.

## Note
This file intentionally does not contain passwords. Use the live OverTheWire challenge to obtain them.
