# 🔐 VAPT Lab: Metasploit Exploitation (Metasploitable2)

## 📌 Overview

This project demonstrates a complete Vulnerability Assessment and Penetration Testing (VAPT) workflow using Kali Linux and Metasploitable2.

The objective was to identify, exploit, and analyze real-world vulnerabilities in a controlled lab environment.

## ⚙️ Lab Setup

* Attacker: Kali Linux
* Target: Metasploitable2
* Tools: Nmap, Metasploit, Enum4linux, SMBClient

## 🔍 Reconnaissance

* Discovered target using netdiscover
* Performed service enumeration using Nmap

### Key Findings:

* FTP (vsftpd 2.3.4)
* SMB (Samba 3.0.20)
* HTTP, SSH, MySQL

## 💥 Exploitation

### 1. vsftpd 2.3.4 Backdoor

* Identified vulnerable FTP service
* Exploited using Metasploit
* Gained root shell access

### 2. SMB usermap_script (RCE)

* Enumerated SMB shares using null session
* Identified vulnerable Samba version
* Achieved remote command execution

## 🧠 Post-Exploitation

* Verified root access using `whoami`
* Collected system information (`uname -a`)
* Explored file system

## 📸 Screenshots

(See /screenshots folder)

## ⚠️ Impact

* Unauthorized remote access
* Full system compromise
* Exposure of sensitive services

## 🛡️ Mitigation

* Update vulnerable services (vsftpd, Samba)
* Disable anonymous access
* Apply proper authentication controls

## 🚀 Skills Demonstrated

* Network Scanning
* Vulnerability Identification
* Exploitation using Metasploit
* Post-Exploitation Techniques
* Security Reporting

## 📎 Author

Logesh – Cybersecurity Enthusiast | VAPT Learner
