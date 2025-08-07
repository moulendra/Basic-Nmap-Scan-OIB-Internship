# Basic-Nmap-Scan-OIB-Internship
This repository contains my solution for Task 1 (Basic Network Scanning with Nmap) for the Oasis Infobyte Security Analyst Internship.
# Basic Network Scanning with Nmap

This repository contains my solution for **Task 1: Basic Network Scanning with Nmap** as part of the **Oasis Infobyte Security Analyst Internship (July P1 Batch)**.

## 📌 Objective

To perform a basic network scan using Nmap to identify open ports and services on a target machine (Metasploitable2).

---

## 🛠️ Tools Used

- **Kali Linux (Virtual Machine)**
- **Nmap**
- **Metasploitable2 (as the vulnerable target system)**

---

## 📸 Screenshots

Screenshots of the Nmap scan output are included in this repository:
- `Screenshot_2025-08-07_09-07-36.png`
- `Screenshot_2025-08-07_09-08-40.png`

---

## 📄 Output File

- `nmap_scan_results.txt`: Contains the full scan results.

---

## 📝 Explanation

The Nmap scan was performed on the Metasploitable2 VM using the command:

```bash
```bash
nmap -sV <Target-IP>
This command scans the target for open ports and attempts to detect the versions of the services running on them.

🔍 Example Open Ports Found:
Port 21: FTP — Open

Port 22: SSH — Open

Port 80: HTTP — Open

Each open port represents a potential entry point for attackers. Identifying these helps in analyzing the security posture of a system.

🎯 What I Learned
How to set up a scanning environment using Virtual Machines

How to use Nmap effectively for reconnaissance

How to analyze the basic security posture of a network
Analyze basic security posture of a network.
## 🔗 Internship Details

**Batch**: July-P1  
**Company**: Oasis Infobyte  
**Task**: Task 1 - Basic Network Scanning with Nmap


