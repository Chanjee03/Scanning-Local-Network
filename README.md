# Scanning-Local-Network
Open ports are like doors and windows on your computer network, essential for services like web browsing or email. However, if left unsecured, these ports can become backdoors for attackers, allowing unauthorized access, data theft, or malware infection.
# Scan Your Local Network for Open Ports

## 📌 Objective
Learn to discover open ports on devices in your **local network** to understand potential **network exposure** and identify security risks.

---

## 🛠 Tools Required
- **[Nmap](https://nmap.org/download.html)** (Free, open-source network scanner)
- **[Wireshark](https://www.wireshark.org/download.html)** (Optional, for packet analysis)

---

## 📖 Mini Guide

### 1️⃣ Install Nmap
Download and install Nmap from the [official website](https://nmap.org/download.html) for your operating system.

### 2️⃣ Find Your Local IP Range
- On Windows:  
  ```cmd
  ipconfig
STEPS
1.Install Nmap from official website.
2.Find your local IP range (e.g., 192.168.1.0/24).
3.Run: nmap -sS 192.168.1.0/24 to perform TCP SYN scan.
4.Note down IP addresses and open ports found.
5.Optionally analyze packet capture with Wireshark.
6.Research common services running on those ports.
7.Identify potential security risks from open ports.
8.Save scan results as a text or HTML file.
