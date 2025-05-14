# 🌐 Nmap Reconnaissance Project

This project documents my use of **Nmap** for scanning, identifying hosts, and enumerating services on a local network. It simulates real-world network recon as part of an attacker’s or defender’s toolkit.

## 🛰️ Objectives:
- Discover live hosts in a subnet
- Perform a ping sweep with `nmap -sn`
- Perform service and version detection with `nmap -sV`
- Identify open ports and OS fingerprints with `nmap -O`

## 🧪 Commands Used:
```bash
sudo nmap -sn 10.0.2.0/24
sudo nmap -sV 10.0.2.15
sudo nmap -O 10.0.2.2
