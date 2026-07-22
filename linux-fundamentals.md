# Hack The Box: Linux Fundamentals — What I Learned

## Overview

As part of building my foundation before starting a cybersecurity-specific degree, I completed Hack The Box's **Linux Fundamentals** path. This module covers the core skills needed to operate confidently in a Linux environment — something that's essential for almost every path in security, whether you end up in offensive security, defensive/blue team work, or GRC.

## What the Path Covered

The path was fairly comprehensive, touching on:

- **The Linux filesystem** — directory structure, navigating with `cd`, `ls`, `pwd`, and understanding how everything in Linux is treated as a file
- **Basic commands** — file manipulation (`cp`, `mv`, `rm`, `mkdir`), viewing file contents (`cat`, `less`, `head`, `tail`), and searching (`grep`, `find`)
- **Users and groups** — how Linux manages multiple users, group membership, and why this matters for access control
- **Permissions** — the read/write/execute model, and how ownership works at the user, group, and "other" level
- **Services** — how processes and services run in the background, and basic ways to check what's active on a system

## Where It Clicked (and Where It Didn't, at First)

Permissions and `chmod` were the part that took the longest to actually click. Reading permission strings like `rwxr-xr--` initially felt abstract — I understood the individual letters, but connecting that to *why* it mattered (who can actually do what, and how attackers or admins exploit misconfigured permissions) took some repetition.

What helped was slowing down and mapping out, for a few real files, exactly who could read/write/execute them and why — rather than just memorizing the `chmod` numeric shortcuts (like `755` or `644`). Once I could explain *why* a permission set made sense for a given file, the shortcuts started making sense too instead of feeling like magic numbers.

## Applying It

After finishing the path, I moved on to working directly in **Kali Linux**, which has been a good next step — it's forced me to actually use these fundamentals in a more security-focused context rather than just a generic Linux sandbox.

## What's Next

I'm continuing to build on this foundation while I explore different areas of cybersecurity — including offensive security and blue team / defensive work — before committing to a specialization. If you're on a similar path or have advice on what helped you most early on, I'd love to hear it.

---
*Learning cybersecurity through Hack The Box, YouTube, and self-study. Open to connecting with others in the field.*
