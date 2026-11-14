# Security policy

This repository holds build sources for DescartesOS on the CMF Phone 1 (Tetris).
It is maintained by one person and has no release schedule or support window.

## Reporting a problem

Use GitHub's private vulnerability reporting on this repository (Security tab,
"Report a vulnerability") for anything that could put a phone or its data at
risk: a SELinux rule that is too broad, a file permission that exposes a kernel
node, a leaked key or token, or a flaw in Tetris Parts. Please include the ROM
build date and the steps to reproduce.

Other bugs can go in a public issue.

## Scope

Proprietary firmware and vendor blobs are extracted from Nothing's stock
software and are not patched here. Problems inside those binaries should be
reported to Nothing.
