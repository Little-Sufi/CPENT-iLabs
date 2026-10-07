# 🛡️ CPENT v2 iLabs — Practical Penetration Testing Vault

[![Certification](https://img.shields.io/badge/Certification-CPENT%20v2%20%7C%20LPT%20Master-orange?logo=security)](https://www.eccouncil.org/programs/certified-penetration-testing-professional-cpent/)
[![Obsidian Ready](https://img.shields.io/badge/Obsidian-Ready%20Vault-purple?logo=obsidian)](https://obsidian.md)
[![Status](https://img.shields.io/badge/iLabs-Modules%2003--14%20Complete-green)]()
[![License](https://img.shields.io/badge/License-MIT-blue)](LICENSE)

Created & Maintained by **[Amar Sufiyan KC (@Little-Sufi)](https://github.com/Little-Sufi)**

---

## 🔬 Vault Overview

The **CPENT v2 iLabs Vault** is an advanced, hands-on offensive security laboratory manual and penetration testing playbook designed around the rigorous **EC-Council Certified Penetration Testing Professional (CPENT v2)** curriculum.

Unlike entry-level certifications, CPENT tests real-world multi-stage offensive campaigns, including **double pivoting**, **binary analysis & 32/64-bit buffer overflows**, **Active Directory Kerberos exploitation**, **OT/IoT hardware hacking**, and **perimeter defense evasion**. This vault houses meticulously documented walkthroughs, command logs, verified assessment answers, mapped screenshot assets, and linked PDF lab manuals.

---

## 🗺️ Master Module Architecture

| Module | Domain | Core Methodologies & Exploitation Vectors |
|:---:|:---|:---|
| **03** | **OSINT & Attack Surface** | Domain intelligence, employee harvesting, passive asset mapping, automated OSINT |
| **04** | **Social Engineering** | Social-Engineer Toolkit (SET), Dark-Phish, credential sniffing, payload generation |
| **05** | **Web App Pentesting** | SQLi, Stored/Reflected XSS, LFI/RFI, CSRF, IDOR, Log4j reverse shells, Burp Suite, WPScan |
| **06** | **API & JWT Pentesting** | BOLA/IDOR, BFLA, NoSQL injection, secret key brute-forcing, hidden endpoint discovery |
| **07** | **Perimeter Evasion** | Firewall & IDS/IPS evasion, custom encoding, decoy packet crafts, tunneling bypasses |
| **08** | **Windows Privilege Escalation** | Token impersonation, Potato exploits, service misconfigurations, UAC bypass, SAM dumping |
| **09** | **Active Directory Pentesting** | Kerberoasting, AS-REP roasting, BloodHound path analysis, Mimikatz, Pass-the-Hash |
| **10** | **Linux Privilege Escalation** | SUID abuse, sudo privileges, kernel exploitation, cronjob hijacking, capabilities |
| **11** | **Binary Exploitation & Fuzzing**| GDB, Immunity Debugger, Mona.py, 32/64-bit stack overflows, bad character elimination |
| **12** | **Lateral Movement & Pivoting** | Single & double pivoting, Chisel, SSH dynamic tunneling, Proxychains, Socat relays |
| **13** | **IoT Penetration Testing** | Firmware analysis, UART/JTAG pinout identification, MQTT broker inspection, CoAP |
| **14** | **Reporting & Post-Testing** | Executive report preparation, technical CVSS risk matrix, artifact hygiene |

---

## 📁 Repository Structure

```text
CPENT iLabs/
├── 00 - CPENT iLabs Master Index.md        # Master Navigation & PDF link index
├── Module 03 - OSINT and Attack Surface/   # Lab walkthroughs & linked PDF guides
├── Module 04 - Social Engineering/         # Phishing & credential harvesting labs
├── Module 05 - Web Application Pentesting/ # Deep OWASP web exploitation guides
├── Module 06 - API and JWT Pentesting/     # Modern API vulnerability labs
├── Module 07 - Perimeter Defence Evasion/  # Firewall, IDS & evasion walkthroughs
├── Module 08 - Windows PrivEsc/            # Local Windows privilege escalation
├── Module 09 - Active Directory Pentest/   # Enterprise AD domain exploitation
├── Module 10 - Linux PrivEsc/              # Linux kernel, SUID & service privesc
├── Module 11 - Reverse Engineering & Pwn/  # Fuzzing, buffer overflows & shellcoding
├── Module 12 - Lateral Movement & Pivoting/# Dynamic SSH, Chisel & double pivots
├── Module 13 - IoT Penetration Testing/    # Embedded hardware & firmware testing
├── Module 14 - Report Writing/             # Post-engagement reporting templates
└── Lab Manuals/                            # Full screenshot archives and lab guides
```

---

## 🚀 How to Navigate in Obsidian

1. Open Obsidian -> **Open folder as vault** -> Select `CPENT iLabs`.
2. Start by opening **`00 - CPENT iLabs Master Index.md`**.
3. All module markdown files and embedded PDF manuals (`[[...pdf|📄 PDF Export]]`) open natively inside Obsidian's workspace without external viewers.

---

## ⚖️ Legal Disclaimer

> **NOTICE:** All technical material, scripts, and vulnerability exploitation procedures contained within this repository are for educational instruction and authorized laboratory research only. Testing targets without documented permission is strictly prohibited by law.
