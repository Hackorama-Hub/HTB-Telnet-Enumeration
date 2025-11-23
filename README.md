# HTB – Telnet Enumeration Report

## 📌 Overview
This report covers the enumeration of the Telnet (port 23) service during a HackTheBox machine assessment. The objective is to identify service information, potential weaknesses, and gather data useful for further exploitation.

---

## 🖥 Target Information
| Item | Details |
|------|---------|
| **Machine Name** | Replace with machine name |
| **Machine IP** | `10.129.158.89` |
| **Difficulty** | Beginner |
| **Objective** | Enumerate Telnet service on port 23 |

---

## 🔍 Step 1 — Initial Port Scan
Performed an Nmap scan to detect whether Telnet (port 23) is open.

```bash
nmap -sV -sC -p 23 10.129.158.89
