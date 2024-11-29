# Gobuster-Hacking
# Ethical Hacking Lab: Web Directory Enumeration with Gobuster

## Overview

This project demonstrates the use of **Gobuster**, a powerful directory and file brute-forcing tool, in an ethical hacking scenario. The goal was to perform directory enumeration on a simulated target, `http://fakebank.thm`, to identify hidden directories and files that could potentially expose vulnerabilities.

The lab was conducted in a controlled environment as part of an ethical hacking learning exercise on the TryHackMe platform.

---

## Objective

The primary objective of this lab was to:

1. Understand how to use **Gobuster** for directory enumeration.
2. Identify potentially hidden directories or files that could reveal sensitive information.
3. Practice safe and ethical hacking techniques in a sandboxed environment.

---

## Tools Used

- **Operating System**: Linux (Ubuntu)
- **Gobuster**: v2.0.1
- **Wordlist**: `wordlist.txt` (customizable for testing specific directories)

---

## Commands Used

The following command was executed to enumerate directories on the target:

```bash
gobuster -u http://fakebank.thm -w wordlist.txt dir
