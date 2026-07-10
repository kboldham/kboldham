
<div align="center">

# Kyle Oldham

### Cybersecurity & IT Infrastructure · Raleigh–Durham, NC

I build production-shaped IT environments, run them like real support queues, and document every ticket end to end.
**B.S. Information Technology (Cybersecurity), Magna Cum Laude · CompTIA Security+**

Open to **IT Support, Help Desk, Systems Administrator, IAM Analyst,** and **SOC Analyst** roles.

<a href="https://www.linkedin.com/in/kyle-oldham-922607266/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:kyleboldham@gmail.com"><img src="https://img.shields.io/badge/Email-Reach_out-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

</div>

---

## Contents

- [About](#about)
- [Certifications](#certifications)
- [Core Skills](#core-skills)
- [Homelab Environment](#homelab-environment)
- [Featured Projects](#featured-projects)

---

## About

I'm a recent **North Carolina Central University** graduate focused on the identity, infrastructure, and support side of IT. I learn by building the real thing and then operating it: a multi-VM Proxmox lab with a segmented corporate subnet, a Windows Server 2022 Active Directory domain, a Microsoft 365 and Entra ID tenant, endpoint management through Intune and NinjaOne, and a ServiceNow instance where the resulting work actually gets ticketed and closed.

Every task in my lab is documented the way it would be handed off to a teammate — issue, steps, verification, resolution. That habit is the point of the portfolio, not a side effect of it.

- **B.S. Information Technology — Cybersecurity Concentration**, NCCU · *Magna Cum Laude*
- **CompTIA Security+** certified · currently studying for **CompTIA Network+**
- Operating a full Windows/M365 support environment end to end — provisioning, policy, permissions, lifecycle, offboarding
- Building **Oldham Technology Group** — Microsoft 365 identity-lifecycle automation for small professional-services 
- **Raleigh–Durham, NC** · open to on-site, hybrid, and remote

---

## Certifications

| Credential | Status |
| :--- | :--- |
| **CompTIA Security+ (SY0-701)** | Certified |
| **CompTIA Network+ (N10-009)** | In progress |

---

## Core Skills

| Category | Skills |
| :--- | :--- |
| **Help Desk & Service Delivery** | ServiceNow ITSM, incident and request management, ticket documentation, end-user support, escalation and resolution workflow |
| **Identity & Access Management** | Active Directory, Microsoft Entra ID, user lifecycle (joiner/mover/leaver), security and distribution groups, role review, MFA enforcement |
| **Systems Administration** | Windows Server 2022, Group Policy, domain join, SMB file shares, NTFS and share permissions, least-privilege access design |
| **Cloud & Modern Workplace** | Microsoft 365 Admin Center, Exchange Online, SharePoint Online, Microsoft Teams, license administration |
| **Endpoint & Patch Management** | Microsoft Intune (MDM/MAM), NinjaOne, device enrollment, compliance policy, patch deployment |
| **Security Operations** | Wazuh SIEM, endpoint telemetry, alert triage, MITRE ATT&CK mapping, vulnerability scanning |
| **Scripting & Automation** | PowerShell, Microsoft Graph PowerShell SDK, Bash, Python |

---

## Tech & Tools

**Identity, Cloud & Endpoint**

![Microsoft Entra ID](https://img.shields.io/badge/Microsoft_Entra_ID-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Microsoft 365](https://img.shields.io/badge/Microsoft_365-D83B01?style=flat-square&logo=microsoftoffice&logoColor=white)
![Intune](https://img.shields.io/badge/Intune-MDM%2FMAM-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![NinjaOne](https://img.shields.io/badge/NinjaOne-Patch_Management-1F6FEB?style=flat-square)
![Microsoft Graph](https://img.shields.io/badge/Microsoft_Graph-PowerShell_SDK-2C2C2C?style=flat-square&logo=microsoft&logoColor=white)

**Infrastructure & Directory Services**

![Windows Server](https://img.shields.io/badge/Windows_Server_2022-0078D6?style=flat-square&logo=windows&logoColor=white)
![Active Directory](https://img.shields.io/badge/Active_Directory-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox_VE-E57000?style=flat-square&logo=proxmox&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu_24.04_LTS-E95420?style=flat-square&logo=ubuntu&logoColor=white)

**Service Management & Security**

![ServiceNow](https://img.shields.io/badge/ServiceNow-81B5A1?style=flat-square&logo=servicenow&logoColor=white)
![Wazuh](https://img.shields.io/badge/Wazuh-SIEM-3A8BBB?style=flat-square&logo=wazuh&logoColor=white)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-Mapping-C8102E?style=flat-square)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white)

**Scripting**

![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## Homelab Environment

A self-hosted Proxmox VE environment simulating small-business IT infrastructure — built to generate real operational work, not just initial setup.

| Layer | Components |
| :--- | :--- |
| **Hypervisor** | Proxmox VE |
| **Directory Services** | Windows Server 2022 domain controller (`DC01`), joined Windows clients (`MANAGED-01`, `MANAGED-02`) |
| **Network** | NAT'd corporate subnet `10.10.0.0/24` · isolated segment for lab-only traffic |
| **Cloud Identity** | Microsoft Entra ID tenant · Microsoft 365 Admin Center |
| **Endpoint Management** | Microsoft Intune · NinjaOne |
| **Security Monitoring** | Wazuh SIEM (`10.10.0.30`) with agents on managed endpoints |
| **Service Management** | ServiceNow ITSM instance — every task below is opened, worked, and closed as a ticket |

---

## Featured Projects

### IT Support & Help Desk Environment
Help desk operations across Active Directory, Microsoft 365, Entra ID, Intune, and NinjaOne — user provisioning, Group Policy, file share permissions, license administration, MFA enrollment, patch management, and full employee lifecycle including onboarding and offboarding. Each task is documented as a worked ServiceNow ticket with steps, verification, and screenshots.

> **Demonstrates:** Help desk workflow, Windows Server administration, Microsoft 365 administration, IAM, endpoint management, IT documentation.
>
> [`kboldham/it-support-environment`](https://github.com/kboldham/it-support-environment)

### Proxmox SIEM Lab
A segmented Proxmox VE environment, Wazuh all-in-one SIEM, managed Windows and Ubuntu Linux endpoints, and a Kali linux attack vm separatedplit across a corporate subnet and an isolated segment. Covers agent enrollment, detection validation, and alert triage mapped to MITRE ATT&CK.

> **Demonstrates:** Network segmentation, Log analysis, SIEM deployment and tuning, attack and detect strategies.
>
> [`kboldham/proxmox-siem-lab`](https://github.com/kboldham/proxmox-siem-lab)

### AWS Lab
Coming Soon ...
>


---

