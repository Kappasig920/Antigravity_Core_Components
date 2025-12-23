---
description: Preparing the macOS system for optimization and diagnostics
---

<!-- @format -->

Efficiently audit the system state before applying tweaks.

1.  **Check OS and Kernel version.**
    // turbo
    `bash
    uname -a && sw_vers
    `
2.  **List heavy background processes.**
    // turbo
    `bash
    top -l 1 -o cpu -n 10
    `
3.  **Audit current login items.**
    // turbo
    `bash
    osascript -e 'tell application "System Events" to get name of every login item'
    `
4.  **Report findings and suggest next optimization steps.**
