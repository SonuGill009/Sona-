#  SSH Honeypot using Paramiko

This is a lightweight SSH honeypot built in Python using the [Paramiko](https://www.paramiko.org/) library.  
It simulates a basic SSH server and logs all login attempts (username, password, and IP address) to help detect unauthorized access attempts.

> ⚠️ For educational and research use only.

---

## 🔍 What Is a Honeypot?

A honeypot is a security mechanism that creates a fake service to lure and monitor attackers.  
This project acts like a real SSH server, but logs all connection attempts without granting access.

---

## ✨ Features

- Simulates an SSH server (default port: `2200`)
- Logs:
  - IP address of the client
  - Username and password used
- Multithreaded: Handles multiple connections at once
- Easy to run and extend

---

## ⚙️ Requirements

- Python 3.x
- `paramiko` library

Install with:

```bash
pip install paramiko
