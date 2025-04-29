# finance-sector-vuln-assessment
Cybersecurity capstone project on vulnerability assessment and exploitation in a finance sector simulation

# Cybersecurity Capstone Project – Vulnerability Assessment in Finance Sector

## 🔐 Project Overview
This project simulates a real-world vulnerability assessment and exploitation workflow in a finance sector environment. The target system is a Windows 10 VM assessed using industry-standard tools such as Nmap, Nessus, and Metasploit on Kali Linux.

## 🧰 Tools & Technologies Used
- Kali Linux
- Windows 10 VM
- Nmap
- Nessus
- Metasploit Framework
- EternalBlue Exploit (MS17-010)

## 🛠️ Steps Performed
1. Identified Windows 10 machine and configured scripts.
2. Installed and set up **Nessus** and **Metasploit** on Kali Linux.
3. Used **Nmap** to discover network and identify live hosts.
4. Detected EternalBlue (MS17-010) vulnerability via **Nessus scan**.
5. Exploited the vulnerability using **Metasploit**.
6. Documented vulnerabilities, impact analysis, and recommendations.

## 📋 Key Observations
- Windows 10 VM was vulnerable to EternalBlue (MS17-010).
- Unpatched SMB service led to high-severity remote code execution risk.
- Demonstrated potential impact on financial data integrity and access.

## ✅ Recommendations
- Apply latest security patches and updates.
- Disable SMBv1 where not needed.
- Implement network segmentation and firewall rules.

## 📄 Report
The full technical report with screenshots and step-by-step guidance is available in the `report/` folder.

## 📂 Project Structure

