# Cloud_MS-Final-Project

# Enterprise Hybrid Infrastructure

> A complete hybrid infrastructure project based on Microsoft Windows Server 2025 and Microsoft Azure.

---

## 📖 Overview

This project simulates the IT infrastructure of a medium-sized company that wants to modernize its on-premises environment while integrating Microsoft Azure services.

The goal is to build a secure, scalable and highly available hybrid infrastructure that demonstrates real-world system administration tasks.

This project combines topics such as:

- Windows Server Administration
- Active Directory
- Hybrid Cloud (Microsoft Azure)
- Security
- Automation
- Backup & Disaster Recovery
- Monitoring
- Documentation

---

## 🎯 Project Goals

- Build a secure Active Directory environment
- Implement centralized user management
- Configure DNS and DHCP
- Deploy a File Server with proper permissions
- Implement High Availability
- Connect the infrastructure to Microsoft Azure
- Automate administrative tasks using PowerShell
- Secure the environment following best practices
- Implement Backup and Disaster Recovery
- Monitor infrastructure health
- Document the complete environment

---

# 🏗 Architecture

```
                +-----------------------+
                |     Microsoft Azure   |
                |-----------------------|
                | Azure Arc             |
                | Azure Backup          |
                | Azure File Sync       |
                | Entra Cloud Sync      |
                | Azure Monitor         |
                | Azure Policy          |
                | Budget                |
                +-----------+-----------+
                            |
                       Internet
                            |
+------------------------------------------------------------+
|                   VMware Workstation                       |
|------------------------------------------------------------|
|                                                            |
|  Server01                  Server02                        |
|  Domain Controller         Domain Controller               |
|  DNS                       DNS                             |
|  DHCP                      DHCP Failover                  |
|  File Server               Replication                     |
|                                                            |
|                  Windows 11 Client                         |
|                                                            |
+------------------------------------------------------------+

```

---

# 🚀 Project Phases

| Phase | Status |
|--------|--------|
| Core Infrastructure | ⏳ |
| High Availability | ⏳ |
| Security | ⏳ |
| Automation | ⏳ |
| Azure Hybrid | ⏳ |
| Disaster Recovery | ⏳ |
| Documentation | ⏳ |

---

# 🛠 Technologies

## Microsoft

- Windows Server 2025
- Windows 11
- Active Directory
- DNS
- DHCP
- Group Policy
- Windows LAPS
- PowerShell
- Windows Server Backup

---

## Azure

- Microsoft Entra ID
- Entra Cloud Sync
- Azure Arc
- Azure File Sync
- Azure Backup
- Azure Monitor
- Log Analytics
- Azure Policy
- Azure Budget

---

## Virtualization

- VMware Workstation

---

# 📂 Repository Structure

```
Enterprise-Hybrid-Infrastructure/

│
├── README.md
├── ROADMAP_EN.md
├── ROADMAP_DE.md
│
├── Documentation/
│
├── Diagrams/
│
├── PowerShell/
│
├── Screenshots/
│
├── Backup/
│
└── Presentation/

```

---

# 📅 Current Plan

### Phase 1

- Active Directory
- DNS
- DHCP
- File Server
- GPO
- Windows Client

### Phase 2

- Second Domain Controller
- Replication
- DHCP Failover

### Phase 3

- Security
- Windows LAPS
- Audit Policies
- PowerShell

### Phase 4

- Azure Integration
- Azure Arc
- Azure Backup
- Azure File Sync
- Cloud Sync

### Phase 5

- Disaster Recovery
- Restore Tests
- Documentation
- Presentation

---

# ⭐ Planned Advanced Features

These features will be implemented after the core project is completed.

- DFS Namespace
- DFS Replication
- Site-to-Site VPN
- Azure Update Manager
- Microsoft Defender for Cloud
- Azure Key Vault
- BitLocker
- IIS
- File Server Resource Manager
- Windows Admin Center
- Multi-Factor Authentication

---

# 📚 Documentation

The project documentation will include:

- Network Diagram
- IP Address Plan
- Active Directory Design
- OU Structure
- Azure Architecture
- Backup Strategy
- Disaster Recovery Plan
- Administration Guide

---

# 📷 Screenshots

Screenshots of each completed phase will be added during the project.

---

# 📜 License

This project was created for educational purposes as part of a Windows Server & Microsoft Azure final project.

---

# 👨‍💻 Author

**Alireza Hadi**

Windows Server • Microsoft Azure • PowerShell • Hybrid Infrastructure
