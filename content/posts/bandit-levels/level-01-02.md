---
title: "OverTheWire Bandit: level-01-02"
draft: false
---

[← Back to Bandit Overview](/posts/overthewire-bandit-writeup/)


# Level 1 -> Level 2

**Goal**
The password for the next level is stored in a file called - located in the home directory.

**Commands Used**
* `ls -la`
* `cat`

**Thought Process**
1. Found the file named `-` in the home directory.
2. Specified the current directory path (`./-`) to read it with `cat`, preventing the terminal from treating `-` as a command option flag.

---
[← Back to Bandit Overview](/posts/overthewire-bandit-writeup/)
