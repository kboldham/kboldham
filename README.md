
<div align="center">

# Kyle Oldham

### Cybersecurity & IT Infrastructure · Raleigh–Durham, NC

**B.S. Information Technology (Cybersecurity) · CompTIA Security+**

Open to **IT Support, Help Desk, and Data Center Technician** roles.

<a href="https://www.linkedin.com/in/kyle-oldham-922607266/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:kyleboldham@gmail.com"><img src="https://img.shields.io/badge/Email-Reach_out-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

</div>

---

## Contents

- [About](#about)
- [Education](#education)
- [Certifications](#certifications)
- [Core Skills](#core-skills)
- [Homelab Environment](#homelab-environment)
- [Projects](#projects)

---

## About

I'm a recent **North Carolina Central University** graduate focused on the identity, infrastructure, and support side of IT.
I build and maintain a homelab to gain hands-on experience with modern IT infrastructure, identity management, endpoint administration, and security operations. Within this environment I practice networking, Windows Server 2022 Active Directory administration, Microsoft 365 and Entra ID management, endpoint administration through Intune, and IT service workflows using ServiceNow. I document every task as though in a production environment, with tickets, steps, and resolution notes. 

## Education 
 **B.S. Information Technology — Cybersecurity**, **North Carolina Central University** (May 2026)
 > Relavant Coursework: 

---

## Certifications

| Credential | Status |
| :--- | :--- |
| **CompTIA Security+ (SY0-701)** | Complete |
| **CompTIA Network+ (N10-009)** | In progress |
| **AWS Certified Cloud Practitioner (CLF-C02)** | In progress |

---

## Core Skills

| Category | Skills |
| :--- | :--- |
| **Help Desk & Service Delivery** | ServiceNow ITSM, incident and request management, ticket documentation, end-user support, escalation and resolution workflow |
| **Identity & Access Management** | Active Directory, Microsoft Entra ID, user lifecycle (joiner/mover/leaver), security and distribution groups, role review, MFA enforcement |
| **Systems Administration** | Windows Server 2022, Group Policy, domain join, SMB file shares, NTFS and share permissions, least-privilege access design |
| **Cloud & Modern Workplace** | Microsoft 365 Admin Center, Exchange Online, SharePoint Online, Microsoft Teams, license administration |
| **Endpoint & Patch Management** | Microsoft Intune (MDM/MAM) device enrollment, compliance policy, patch deployment |
| **Security Operations** | Wazuh SIEM, alert triage, MITRE ATT&CK framework, vulnerability scanning |
| **Scripting & Automation** | PowerShell, Bash, Python |

---

## Tech & Tools

**Identity, Cloud & Endpoint**

![Microsoft Entra ID](https://img.shields.io/badge/Microsoft_Entra_ID-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Microsoft 365](https://img.shields.io/badge/Microsoft_365-D83B01?style=flat-square&logo=microsoftoffice&logoColor=white)
![Intune](https://img.shields.io/badge/Intune-MDM%2FMAM-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![Microsoft Graph](https://img.shields.io/badge/Microsoft_Graph-PowerShell_SDK-2C2C2C?style=flat-square&logo=microsoft&logoColor=white)

**Infrastructure & Directory Services**

![Windows Server](https://img.shields.io/badge/Windows_Server_2022-0078D6?style=flat-square&logo=windows&logoColor=white)
![Active Directory](https://img.shields.io/badge/Active_Directory-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox_VE-E57000?style=flat-square&logo=proxmox&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu_24.04_LTS-E95420?style=flat-square&logo=ubuntu&logoColor=white)

**Service Management & Security**

![ServiceNow](https://img.shields.io/badge/ServiceNow-81B5A1?style=flat-square&logo=servicenow&logoColor=white)
![Wazuh](https://img.shields.io/badge/Wazuh-SIEM-3A8BBB?style=flat-square&logo=wazuh&logoColor=white)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-Framework-C8102E?style=flat-square)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white)

**Scripting**

![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## Homelab Environment

A self-hosted Proxmox VE environment simulating small-business IT infrastructure, built to generate realistic operational scenarios. 

| Layer | Components |
| :--- | :--- |
| **Hypervisor** | Proxmox VE |
| **Directory Services** | Windows Server 2022 domain controller (`DC01`), joined Windows clients (`MANAGED-01`, `MANAGED-02`) |
| **Network** | Simulated corporate subnet `10.10.0.0/24` · Isolated segment for lab-only traffic |
| **Cloud Identity** | Microsoft Entra ID tenant · Microsoft 365 Admin Center |
| **Endpoint Management** | Microsoft Intune|
| **Security Monitoring** | Wazuh SIEM (`10.10.0.30`) with agents on managed endpoints |
| **Service Management** | ServiceNow ITSM Developer Instance used for documenting simulated incidents, requests, and change activities. |

---

## Projects

### IT Support & Help Desk Environment
Simulated help desk operations across Active Directory, Microsoft 365, Entra ID, Intune

> **Demonstrates:** Help desk workflow, Windows Server administration, Microsoft 365 administration, IAM, Endpoint management, IT documentation.
>
> 

### Data Center Environment
Simulate data center operations using Ubuntu Server VMs and a simulated environment in Packet Tracer

> **Demonstrates:**
>
> 


### Wazuh SIEM Lab
A segmented Proxmox VE environment, Wazuh all-in-one SIEM, managed Windows and Ubuntu Linux endpoints, and a Kali Linux attack VM separated across a corporate subnet and an isolated segment. Covers agent enrollment, detection validation, and alert triage mapped to MITRE ATT&CK.

> **Demonstrates:** Network segmentation, Log analysis, SIEM deployment and tuning, Attack and detect strategies.
>
> 

### AWS Lab
In progress ...
>


---
