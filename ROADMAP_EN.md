# Enterprise Hybrid Infrastructure
## Personal Roadmap

---

# Project Progress

- [ ] Phase 1 - Core Infrastructure
- [ ] Phase 2 - High Availability
- [ ] Phase 3 - Security
- [ ] Phase 4 - Automation
- [ ] Phase 5 - Azure Hybrid
- [ ] Phase 6 - Disaster Recovery
- [ ] Phase 7 - Documentation

---

# Phase 1 – Core Infrastructure

**Goal**

Build the company's basic infrastructure.

## VMware

- [ ] Create Server01 VM
- [ ] Create Server02 VM
- [ ] Create Windows 11 VM
- [ ] Configure networking

## Windows Server

- [ ] Install Windows Server 2025
- [ ] Rename the server
- [ ] Configure static IP
- [ ] Configure time zone

## Active Directory

- [ ] Install AD DS
- [ ] Create a new forest
- [ ] Create the domain

## DNS

- [ ] Verify DNS
- [ ] Configure DNS zone
- [ ] Test name resolution

## DHCP

- [ ] Install DHCP
- [ ] Create DHCP scope
- [ ] Test IP assignment

## Windows Client

- [ ] Install Windows 11
- [ ] Join the domain
- [ ] Test user login

## Organizational Units

Create:

- [ ] Management
- [ ] HR
- [ ] Finance
- [ ] IT
- [ ] Sales
- [ ] Warehouse

## Users & Groups

- [ ] Create users
- [ ] Create security groups
- [ ] Assign users to groups

## File Server

- [ ] Create shared folders
- [ ] Configure NTFS permissions
- [ ] Configure share permissions

## Group Policy

- [ ] Password policy
- [ ] Drive mapping
- [ ] Desktop policy
- [ ] Windows Firewall policy

---

# Phase 2 – High Availability

**Goal**

Keep services available if one server fails.

## Domain Controller

- [ ] Install Server02
- [ ] Join the domain
- [ ] Promote to Domain Controller

## Replication

- [ ] Verify AD replication
- [ ] Test user replication

## DNS

- [ ] Verify DNS replication

## DHCP

- [ ] Configure DHCP Failover
- [ ] Test failover

---

# Phase 3 – Security

**Goal**

Secure the infrastructure.

## Windows LAPS

- [ ] Configure LAPS
- [ ] Test password retrieval

## Administrative Accounts

- [ ] Create dedicated admin accounts
- [ ] Remove admin rights from standard users

## Password Policies

- [ ] Minimum length
- [ ] Complexity
- [ ] Expiration

## Account Lockout

- [ ] Configure lockout policy

## Auditing

- [ ] Logon events
- [ ] User changes
- [ ] Group changes

---

# Phase 4 – Automation

**Goal**

Automate administrative tasks.

## PowerShell

- [ ] Import users from CSV
- [ ] Disable users
- [ ] Move users
- [ ] Generate reports

---

# Phase 5 – Azure Hybrid

**Goal**

Connect the on-premises environment to Azure.

## Azure

- [ ] Resource Group
- [ ] Budget

## Microsoft Entra Cloud Sync

- [ ] Install
- [ ] Synchronize users

## Azure File Sync

- [ ] Install agent
- [ ] Synchronize folders

## Azure Backup

- [ ] Create Recovery Services Vault
- [ ] Configure backup
- [ ] Test restore

## Azure Arc

- [ ] Connect Server01
- [ ] Connect Server02

## Azure Monitor

- [ ] Log Analytics
- [ ] Monitoring

## Azure Policy

- [ ] Configure policies
- [ ] Review compliance

---

# Phase 6 – Disaster Recovery

**Goal**

Restore services after failures.

## Backup

- [ ] Windows Server Backup
- [ ] Restore test

## Shadow Copies

- [ ] Enable
- [ ] Test restore

## Active Directory Recycle Bin

- [ ] Enable
- [ ] Restore deleted users

## Disaster Simulation

- [ ] Shut down a Domain Controller
- [ ] Test user logon
- [ ] Test DNS
- [ ] Test DHCP
- [ ] Restore files

---

# Phase 7 – Documentation

- [ ] Network diagram
- [ ] IP addressing plan
- [ ] OU structure
- [ ] Azure architecture
- [ ] Backup strategy

---

# Advanced Features (Optional)

- [ ] DFS Namespace
- [ ] DFS Replication
- [ ] Site-to-Site VPN
- [ ] Azure Update Manager
- [ ] Microsoft Defender for Cloud
- [ ] Azure Key Vault
- [ ] BitLocker
- [ ] IIS
- [ ] File Server Resource Manager
- [ ] Windows Admin Center
- [ ] Multi-Factor Authentication
- [ ] Protected Users

---

# Final Checklist

- [ ] Test all services
- [ ] Capture screenshots
- [ ] Measure recovery times
- [ ] Complete documentation
- [ ] Prepare final presentation
