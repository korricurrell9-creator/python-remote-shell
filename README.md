# Python Remote Shell

![Python](https://img.shields.io/badge/Python-3.12-blue)
![License](https://img.shields.io/badge/License-MIT-green)

A simple Python TCP server/client setup for remote command execution.  
Control a server running on **Kali Linux**, **PC**, or **Android (Termux)** from a client machine.

---

## Table of Contents
- [Requirements](#requirements)
- [Installation](#installation)
- [Server Setup](#server-setup)
  - [Kali Linux / PC](#server-on-kali-linux)
  - [Android (Termux)](#server-on-android-termux)
- [Client Setup](#client-setup)
- [Example Commands](#example-commands)
- [Troubleshooting](#troubleshooting)
- [Safety / Disclaimer](#safety--disclaimer)

---

## Requirements

- Python 3.x on both server and client  
- Git (if cloning from GitHub)  
- Termux installed on Android device (if running server on Android)  
- Wi-Fi connection on the same network for client/server communication

---

## Installation

1. Clone this repository on all devices that need the server or client:

```bash
git clone https://github.com/korricurrell9-creator/python-remote-shell.git
cd python-remote-shell
