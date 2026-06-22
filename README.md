# 🛡️ Network Security: Python-Based Port Scanner

## 📋 Overview
An efficient, asynchronous network utility built in Python 3 utilizing socket programming to audit and identify active services on a target host. This tool resolves hostnames, iterates through high-risk corporate ports, and flags open entry points—simulating the initial reconnaissance phase of a security audit.

## ✨ Key Features
* **DNS Resolution:** Automatically resolves target domain names (e.g., `scanme.nmap.org`) to valid IPv4 addresses.
* **Targeted Scanning:** Audits critical system and web ports (21, 22, 23, 25, 53, 80, 443, etc.).
* **Service Mapping:** Correlates open ports to standard networking protocols (SSH, HTTP, HTTPS, FTP).
* **Graceful Exception Handling:** Features built-in error handling for invalid hostnames, lost network connectivity, and manual user interrupts (Ctrl+C).

## 🛠️ Technologies & Libraries
* **Language:** Python 3.x
* **Core Libraries:** `socket` (Network interface abstraction), `sys` (Runtime environment control), `datetime` (Scan duration logging).

## 🚀 How to Run the Tool

1. **Clone the Repository:**
   ```bash
   git clone https://github.com
   cd Python-port-scanner
   ```

2. **Execute the Script:**
   ```bash
   python port_scanner.py
   ```

3. **Input Target:** Enter the IP address or domain name you have explicit authorization to scan.

## 📊 Sample Execution Output
```text
==================================================
🛡️ STARTING NETWORK RECONNAISSANCE SCAN
Target Host: scanme.nmap.org (45.33.32.156)
Time Started: 2026-06-23 01:45:00
==================================================

[+] [OPEN] Port 22   - Service: SSH (Secure Shell)
[+] [OPEN] Port 80   - Service: HTTP (Hypertext Transfer Protocol)
[+] [OPEN] Port 443  - Service: HTTPS (Secure HTTP)

==================================================
Scan completed in: 0:00:04.128392
==================================================
```

## 🧠 Core Competencies Demonstrated
* **Network Infrastructure:** Deep understanding of the TCP/IP stack, handshake processes, and port assignment.
* **Scripting & Automation:** Creating modular, reusable automation scripts for security infrastructure tasks.
* **Security Auditing Basics:** Demonstrating knowledge of the reconnaissance phase within ethical hacking frameworks.

---

