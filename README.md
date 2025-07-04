# 🕵️‍♂️ OsintSpy

**OsintSpy** is a powerful, modular, and extensible OSINT (Open Source Intelligence) automation tool written in Python. It allows security researchers, ethical hackers, and investigators to gather, analyze, and save publicly available intelligence on any target — be it an IP address, domain, email, username, or phone number.

This tool is designed for **real-world usage**, with live-ready functionality, verbose mode, and multi-format output including XML, JSON, and TXT.

---

## ⚙️ Features

- 🌐 Collect intelligence from multiple public sources
- 🔍 Supports user input for:
  - Domains
  - IP addresses
  - Usernames
  - Emails
  - Phone numbers
- 🧾 Saves all collected data in:
  - `.xml`
  - `.json`
  - `.txt`
- 📣 Verbose mode to display internal execution
- 📤 Export-ready: Save output with custom filename
- ✅ Ready to be deployed as a live GitHub repository

---

## 🚀 Quick Start

### 🛠️ Requirements

- Python 3.x
- `requests`, `bs4`, `lxml`, `xmltodict` (install via `requirements.txt`)

```bash
pip install -r requirements.txt
