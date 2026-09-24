# Bandit Level 12 → 13

## Goal
Reverse a hexdump and repeatedly decompress the resulting file until the password appears.

## Solution path

```bash
xxd -r data.txt data.bin && file data.bin
```

## What I learned
Repeated format identification and decompression. Use file after every step, then the matching decompressor (gzip -d, bzip2 -d, tar -xf, etc.).

## Note
This file intentionally does not contain passwords. Use the live OverTheWire challenge to obtain them.
