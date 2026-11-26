---
date: "2026-11-24"
title: "OverTheWire Bandit: level-09-10"
draft: false
---

[← Back to Bandit Overview](/posts/overthewire-bandit-writeup/)


# Level 9 -> Level 10

**Goal**
The password for the next level is stored in the file data.txt in one of the few human-readable strings, preceded by several ‘=’ characters.

**Commands Used**
*  `strings`
*  `grep`

**Thought Process**
1. Used the `strings` command to extract readable text from the binary file.
2. Used a pipe (`|`) to pass the output to `grep`.
3. Used `grep` to find strings preceded by several `=` characters.

**Key Concepts**

- `strings`: Extracts readable text strings from binary files.

---
[← Back to Bandit Overview](/posts/overthewire-bandit-writeup/)
