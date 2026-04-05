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

## Screenshots 

<img width="1048" height="499" alt="1" src="https://github.com/user-attachments/assets/de91109e-0792-4248-bbc5-e6c680f7124b" />

<img width="963" height="722" alt="2" src="https://github.com/user-attachments/assets/2210ce85-4b90-48be-8384-1d38fb50ad80" />

<img width="1018" height="491" alt="3" src="https://github.com/user-attachments/assets/1471ccfa-35ca-49e1-a127-1fdc35ec1dfe" />

<img width="1028" height="510" alt="4" src="https://github.com/user-attachments/assets/bdabe541-d27b-466c-a847-4ac192a22755" />

<img width="1026" height="488" alt="5" src="https://github.com/user-attachments/assets/d79b241a-d0ee-4668-9512-68394694f80e" />

<img width="1018" height="494" alt="6" src="https://github.com/user-attachments/assets/bf8a57d8-8b73-4c84-b595-dabd755e7bdc" />

<img width="997" height="465" alt="7" src="https://github.com/user-attachments/assets/51317da7-71ed-4b37-97b3-ed859f5ec41f" />

<img width="984" height="481" alt="8" src="https://github.com/user-attachments/assets/35a84c6b-072d-4c20-874c-053ae2a86e88" />

<img width="621" height="673" alt="9,10" src="https://github.com/user-attachments/assets/f5337432-ed3e-4d66-a76b-40355d4b84f7" />

<img width="608" height="628" alt="11,12" src="https://github.com/user-attachments/assets/327b1c67-cc92-422a-93fa-ee03cadbdae3" />

<img width="624" height="672" alt="13,14" src="https://github.com/user-attachments/assets/40278a7d-2b37-4566-aa98-c9836f5f3c80" />






