<div align="center">

# Kyle Oldham

### IT Infrastructure & Networking · Raleigh-Durham, NC

**B.S. Information Technology (Cybersecurity) · CompTIA Security+**

Open to **IT Support, Help Desk, Network Technician, and Data Center Technician** roles.

<a href="https://www.linkedin.com/in/kyle-oldham-922607266/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:kyleboldham@gmail.com"><img src="https://img.shields.io/badge/Email-Reach_out-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

</div>

---

## Contents

- [About](#about)
- [Education](#education)
- [Certifications](#certifications)
- [Core Skills](#core-skills)
- [Tech and Tools](#tech-and-tools)
- [Homelab Environment](#homelab-environment)
- [Projects](#projects)

---

## About

I am a recent **North Carolina Central University** graduate focused on the networking, systems administration, and support side of IT. I build and maintain a homelab to gain hands on experience with core IT infrastructure: virtualization, firewall and network segmentation, Windows Server and Active Directory administration, Linux server administration, and SIEM based log analysis. I document every task as though in a production environment, with clear steps, screenshots, and resolution notes.

## Education

**B.S. Information Technology, Cybersecurity**, North Carolina Central University, Magna Cum Laude (Graduated 2026)

Relevant Coursework: Project Management, Systems Analysis and Design (SDLC), Business Management, Marketing, Microeconomics

---

## Certifications

| Credential | Status |
| :--- | :--- |
| **CompTIA Security+** | Complete |
| **CompTIA Network+** | In progress |
| **EC-Council AI Essentials** | Complete |

---

## Core Skills

| Category | Skills |
| :--- | :--- |
| **Networking** | TCP/IP, IPv4, subnetting, firewall and router configuration (pfSense), network segmentation, DHCP, DNS, connectivity troubleshooting (ipconfig, ping, tracert, nslookup) |
| **Routing and Switching** | Cisco IOS configuration, static routing, VLANs (Cisco Packet Tracer) |
| **Systems and Identity** | Windows Server 2025, Windows 11 troubleshooting, Active Directory, Group Policy, DNS and DHCP administration |
| **Linux Administration** | Ubuntu Server, systemd services, SSH, user and permission management, log review (auditd) |
| **Security Operations** | Splunk SIEM deployment and log searching, Windows event logs, Sysmon |
| **Scripting and Tools** | PowerShell, basic Python, Proxmox VE, Git and GitHub |

---

## Tech and Tools

**Infrastructure and Virtualization**

![Proxmox](https://img.shields.io/badge/Proxmox_VE-E57000?style=flat-square&logo=proxmox&logoColor=white)
![pfSense](https://img.shields.io/badge/pfSense-212121?style=flat-square&logo=pfsense&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu_Server-E95420?style=flat-square&logo=ubuntu&logoColor=white)

**Identity and Directory Services**

![Windows Server](https://img.shields.io/badge/Windows_Server_2025-0078D6?style=flat-square&logo=windows&logoColor=white)
![Active Directory](https://img.shields.io/badge/Active_Directory-0078D4?style=flat-square&logo=microsoft&logoColor=white)

**Networking and Security**

![Cisco](https://img.shields.io/badge/Cisco_IOS-1BA0D7?style=flat-square&logo=cisco&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white)

**Scripting**

![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## Homelab Environment

A self hosted Proxmox VE environment simulating small business IT infrastructure, built to generate realistic troubleshooting and support scenarios.

| Layer | Components |
| :--- | :--- |
| **Hypervisor** | Proxmox VE |
| **Firewall and Routing** | pfSense, segmented into CORP, DMZ, and SOC zones |
| **Directory Services** | Windows Server 2025 domain controller (`DC01`), joined Windows 11 client (`WIN11`) |
| **Linux Server** | Ubuntu Server on the DMZ segment (`WEB01`) |
| **Security Monitoring** | Splunk on a dedicated host (`SIEM01`) with log forwarding from Windows endpoints |
| **Routing and Switching Practice** | Cisco Packet Tracer, separate from the Proxmox environment |

---

## Projects

### Windows Client and Domain Troubleshooting
Built a Windows Server domain controller and joined a Windows 11 client, then reproduced and diagnosed a domain join failure caused by client DNS misconfiguration.

> **Demonstrates:** Active Directory administration, Group Policy, account support, DNS and connectivity troubleshooting.

### Network and Linux Administration
Configured firewall and routing policy on pfSense to segment a multi zone network, validated the segmentation in both directions, and administered a Linux server.

> **Demonstrates:** Firewall configuration, network segmentation, DHCP and DNS administration, basic Linux administration.

### SIEM Log Analysis with Splunk
Deployed a Splunk instance, configured log forwarding from a Windows domain, and verified the SIEM was receiving and searchable data.

> **Demonstrates:** SIEM deployment, Universal Forwarder configuration, basic log searching.

### Cisco Router and Switch Configuration
Built and configured a small routed network in Cisco Packet Tracer, including interface addressing, a serial WAN link, static routing, and a VLAN.

> **Demonstrates:** Cisco IOS configuration, static routing, VLANs, network verification.

---
