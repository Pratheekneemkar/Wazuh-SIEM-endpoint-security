# 🛡️ Wazuh SIEM – Endpoint Security & File Integrity Monitoring Lab

## 📌 Project Overview
This project demonstrates the deployment of an enterprise-grade **Security Information and Event Management (SIEM)** system using **Wazuh** to monitor a **Windows endpoint** from a centralized **Ubuntu-based security server**. The lab simulates how modern **Security Operations Centers (SOCs)** detect suspicious activities such as unauthorized file changes, hidden files, and integrity violations in real time.

---

## 🧱 Lab Architecture
The environment [View Network Architecture Diagram](architecture/wazuh_home_lab_network_diagram.drawio.png) consists of two systems connected via a private VirtualBox network:

- **Windows Host** – Runs the **Wazuh Agent**  
- **Ubuntu Virtual Machine** – Runs the **Wazuh Manager, Indexer, and Dashboard**

All security telemetry (system logs, file integrity events, and cryptographic hash data) is securely transmitted from the Windows endpoint to the Ubuntu SIEM server for centralized analysis.


---

## 🛠️ Technologies Used
- Wazuh SIEM & XDR  
- Ubuntu Server  
- Windows 10 / 11  
- VirtualBox  
- OSSEC Agent  
- File Integrity Monitoring (FIM)  
- Cryptographic hashing (Checksum & SHA-1)

---

## 🎯 Project Objectives
- Deploy a centralized SIEM platform  
- Monitor a Windows endpoint using a Wazuh agent  
- Detect file creation, modification, deletion, and hidden files  
- Enable cryptographic file integrity verification  
- Visualize and analyze security alerts using the Wazuh dashboard  

---

## ⚙️ Implemented Features
- Real-time File Integrity Monitoring  
- Hidden file detection  
- Cryptographic hash verification (checksum & SHA-1)  
- Secure agent onboarding  
- Centralized security event dashboard  

---

## 📸 Snapshots
The [screenshots](screenshots/) folder contains proof of:
- Active Wazuh agent  
- Wazuh dashboard  
- File integrity alerts  
- Hidden file detection  
- Cryptographic hash mismatch alerts  

These screenshots confirm that the SIEM successfully detected and reported security-relevant events.

---

## 📁 Configuration
The Windows agent configuration used in this lab is available in:

[View OSSEC Agent Configuration](configs/ossec.conf)

This file defines the monitored directories, real-time monitoring, and cryptographic hashing options used to detect integrity violations.

---

## 📄 Documentation
A full technical report of the project is included in:

[Download Full Technical Report](report/Report%20Wazuh%20Home%20Lab.pdf)

The report explains the system architecture, implementation steps, testing methodology, and results.

---

## 🧠 Learning Outcomes
This project provided hands-on experience in:
- SIEM deployment and configuration  
- Endpoint security monitoring  
- File integrity and tamper detection  
- Cryptographic validation of files  
- SOC-style security event analysis  

---

## 🔐 Conclusion
This lab demonstrates how enterprise security teams use SIEM platforms like **Wazuh** to monitor endpoints, detect unauthorized changes, and maintain system integrity. It simulates real-world cybersecurity operations in a controlled home-lab environment, providing practical experience in SOC workflows and defensive security monitoring.


