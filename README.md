# Port-Scanner-Using-Python

A simple command-line port scanner tool built with Python that detects open ports on a given IP address or website. This tool helps in the basic vulnerability assessment of a network.

---

## 📌 Problem Statement

Network ports are entry points for services. Open or vulnerable ports can be exploited by attackers. Identifying open ports is essential for securing systems.

---

## 🎯 Objective

Build a Python-based port scanner to:
- Identify open ports on a specific IP address or domain
- Perform fast scanning using multithreading
- Output open ports directly in the terminal

---

## 🧰 Technologies Used

- **Python 3**
- `socket` module
- `threading` module
- Command-Line Interface (CLI)

---

## ⚙️ Features

- Scan up to any custom port range (e.g., 1–1000)
- Multithreaded for faster scanning
- Simple and clean CLI output
- Detects open TCP ports

---

## 🛠️ Requirements

- Python 3.x
- Works on Linux, Windows, macOS
- No external libraries needed

---
## 🚀 How to Run

### 📦 1. Clone or Download
```bash
git clone https://github.com/your-username/port-scanner.git
cd port-scanner
```
2. Run the Script
   ```
   sudo python3 port_scanner.py
 3. Input Example
    ```
    Enter target IP address: 127.0.0.1
    Enter start port: 22
    Enter end port: 22

    ```
    💻 Tested on Kali Linux
     Start SSH Service for Test
    ```
    sudo systemctl start ssh
  
 
🔎 Check Open Port (Optional)
```
sudo ss -tuln | grep :22


    
### 💻 GUI in Action
 | ![](Screenshort/Screenshot_2025-06-24_02_27_07.png) |



 ✅ Built by **Kalpesh Dhamanse** —  [GitHub](https://github.com/Kalpeshdhamanse/Port-Scanner-Using-Python.git)

