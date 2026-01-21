# 🔐 Simple Python Port Scanner

A beginner-friendly **TCP Port Scanner** built using Python to understand basic
networking and cybersecurity reconnaissance techniques.

This project scans common ports on a target IP or domain and identifies whether
they are **open or closed** using socket connections.

---

## 📌 Features
- Scans commonly used ports (FTP, SSH, HTTP, HTTPS, etc.)
- Uses Python’s built-in `socket` module
- Simple and easy-to-understand code
- Timeout handling for faster scanning
- Ethical scanning (authorized targets only)

---

## 🛠 Technologies Used
- Python 3
- Socket Programming

---

## 🚀 How It Works
1. User enters a target IP address or domain
2. The scanner attempts to establish a TCP connection
3. If the connection succeeds → port is **OPEN**
4. If the connection fails → port is **CLOSED**
---

## ▶️ Usage

### Clone the Repository
```bash
git clone https://github.com/thisara-gayantha/Simple-python-port-scanner.git
cd simple-port-scanner
