# Project Status Update

**Project:** Hybrid Enterprise Infrastructure for Nordhafen GmbH

**Date:** November 2026

---

## Current Progress

The project is progressing according to the planned roadmap.

### Completed

- Project planning and infrastructure design
- VMware lab environment
- Windows Server 2025 installation
- Primary Domain Controller (NH-DC01)
- Active Directory Domain Services
- DNS
- DHCP
- Organizational Unit (OU) structure
- User and Group management
- AGDLP permission model
- Dedicated File Server (NH-FS01)
- SMB Shares
- NTFS permissions
- Windows 11 Client (NH-CL01)
- Domain Join
- User authentication tests with multiple domain users

---

## Additional Work (Beyond the Original Scope)

The following components were implemented as additional learning and evaluation tasks:

- Multi-Site infrastructure design
- Ubuntu Gateway
- Netplan configuration
- Routing
- NAT
- Internet connectivity
- Windows RRAS
- Evaluation of Ubuntu Gateway vs. Windows RRAS
- Preparation for Site-to-Site VPN

---

## Work in Progress

- Secondary Domain Controller (NH-DC02)
- Active Directory Replication
- DNS Replication
- DHCP Failover
- Site-to-Site VPN
- Project documentation

---

## Planned Next Steps

1. Promote NH-DC02 to Domain Controller
2. Configure Active Directory Replication
3. Configure DHCP Failover
4. Implement Group Policies (GPO)
5. Configure Shadow Copies
6. Configure Windows Server Backup
7. Implement Windows LAPS
8. Configure Azure Hybrid Services
9. Complete documentation and presentation

---

## Current Project Status

| Area | Status |
|------|--------|
| Core Infrastructure | ✅ Completed |
| Active Directory | ✅ Completed |
| File Server | ✅ Completed |
| Windows Client | ✅ Completed |
| Multi-Site Lab | ✅ Completed |
| RRAS Environment | ✅ Completed |
| Site-to-Site VPN | 🔄 In Progress |
| High Availability | 🔄 In Progress |
| Security | ⏳ Planned |
| Azure Hybrid | ⏳ Planned |
| Documentation | 🔄 In Progress |

---

**Overall Progress:** **~70% Complete**

The core on-premises infrastructure has been successfully deployed and validated. The project is currently focused on implementing high availability, hybrid cloud integration, security hardening, and completing the final documentation.