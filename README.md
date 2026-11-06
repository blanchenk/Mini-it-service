# Mini IT Service

A virtual lab that simulates the IT department of a small company: Active Directory, Group Policies, shared folders with access rights, a ticketing tool and PowerShell automation.

**Status:**  In progress

## Goal
Build and document a complete small-company IT environment, from the domain controller to the end-user PC.

## What I will build
- A Windows Server 2022 domain controller (`company.local`)
- Users, groups and organizational units (OUs)
- Group Policies (screen lock, Control Panel restriction, password policy)
- Shared folders with NTFS permissions per department
- A Windows 11 client joined to the domain
- PowerShell scripts to create and disable user accounts
- A GLPI ticketing tool and a small knowledge base

## Tools
VirtualBox · Windows Server 2022 · Windows 11 · PowerShell · GLPI · Docker

## Repository structure
- `scripts/`: PowerShell automation scripts
- `docs/img/`: screenshots and network diagram
- `kb/`: knowledge base (troubleshooting guides)

## Author
Blanche Nzeyidio Kiangebeni · [LinkedIn](https://www.linkedin.com/in/blanche-nzeyidio-kiangebeni-8b0b32336)