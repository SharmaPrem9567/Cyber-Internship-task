# 🔍 Cybersecurity Internship Task – Nmap Network Scan

## 📌 Task Objective
Conduct a TCP SYN scan on the local network to identify live hosts, open ports, and associated services. Analyze the results to identify potential security risks and document your findings.

---

## 🛠️ Tools Used
- **Nmap** – for scanning the network
- *(Optional)* Wireshark – for packet capture and traffic inspection
- **GitHub** – for documentation and submission

---

## 🧠 Target Network Information
- **Local IP Address**: `192.168.1.18`
- **Subnet Mask**: `255.255.255.0`
- **Default Gateway**: `192.168.1.1`
- **IP Range Scanned**: `192.168.1.0/24`

---

## 🚀 Scan Commands Used

### 🔸 Basic TCP SYN Scan:
```bash
nmap -sS 192.168.1.0/24 -oN scan_results.txt


📂 Files Included in This Submission
scan_results.txt → Nmap output file containing scan details.

README.md → This file explaining the process, results, and risks.

(Optional) screenshots/ folder – Wireshark captures or scan evidence.
