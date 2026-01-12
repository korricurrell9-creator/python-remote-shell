![Python](https://img.shields.io/badge/Python-3.12-blue)
![License](https://img.shields.io/badge/License-MIT-green)

# Python Remote Shell

A simple Python TCP server/client setup for remote command execution.

## Server
- Can run on Kali or Android (Termux)
- Listens on port 9999

## Client
- Connects to server
- Executes commands remotely
# Python Remote Shell

A simple Python TCP server/client setup for remote command execution.  
This project allows you to run a server on **Kali Linux** or **Android (Termux)** and control it remotely from a client machine.

---

## Table of Contents
- [Requirements](#requirements)
- [Setup](#setup)
  - [Server on Kali](#server-on-kali)
  - [Server on Termux](#server-on-termux)
- [Client Usage](#client-usage)
- [Example Commands](#example-commands)
- [Troubleshooting](#troubleshooting)
- [Safety Notes](#safety-notes)

---

## Requirements

- Python 3.x
- Git (for cloning)
- Termux (if running server on Android)
- Wi-Fi connection on same network for client/server communication

---

## Setup

### Server on Kali

1. Clone the repository:
```bash
git clone https://github.com/korricurrell9-creator/python-remote-shell.git
cd python-remote-shell
