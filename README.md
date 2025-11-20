# HTB FTP Enumeration (Port 21)

This repository contains my **FTP (Port 21) enumeration report** from the Hack The Box Starting Point series. The goal of this exercise was to analyze the FTP service, test for anonymous login, capture banners, and document findings with screenshots.

---

## 📌 Overview

FTP (File Transfer Protocol) is an older protocol often found on servers. It is **not encrypted**, making it vulnerable to credential interception. During this task, I performed:

* Port scanning
* Service version detection
* FTP banner grabbing
* Anonymous login testing
* Directory exploration (if allowed)

All findings are documented in the report.

---

## 📄 Report

The full detailed report is available here:

* **REPORT.md** (Markdown version)
* **PDF version** (if available)

---

## 📁 Repository Structure

```
HTB-FTP-Report/
│── README.md
│── REPORT.md
└── screenshots/
        │── nmap_scan.png
        │── ftp_banner.png
        │── anonymous_login.png
```

---

## 🛠 Tools Used

* Nmap
* FTP Client
* Linux Terminal
* Screenshot tools

---

## 🔐 Key Findings

* Port 21 was open and FTP service was active.
* FTP service revealed a server banner during connection.
* Anonymous login test performed (results documented in report).
* FTP is insecure due to plaintext transmission.

---

## ✔️ Recommendations

* Disable FTP in favor of **SFTP/FTPS**.
* Disable **anonymous login** completely.
* Apply proper firewall rules.
* Monitor authentication logs.

---

## 🚀 About This Project

This is part of my ongoing cybersecurity learning journey using **Hack The Box**. Each service (FTP, SSH, Telnet, SMB, etc.) will have its own documented report and GitHub repository.

---

**Author:** Stanley Ebiwanno
**Role:** Security Analyst
