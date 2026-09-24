# Bandit Level 30 → 31

## Goal
Inspect Git tags and find the hidden value in the repository metadata.

## Solution path

```bash
git clone ssh://bandit30-git@bandit.labs.overthewire.org:2220/home/bandit30-git/repo
cd repo
git tag
git show <interesting-tag>
```

## What I learned
Git tags and object inspection.

## Note
This file intentionally does not contain passwords. Use the live OverTheWire challenge to obtain them.
