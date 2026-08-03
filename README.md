# Windows Server Active Directory Lab

## Overview

This repository documents the design, implementation, and administration of an enterprise-style Windows Server environment using Active Directory Domain Services (AD DS). The lab simulates a multi-domain infrastructure by deploying two independent Active Directory forests, configuring identity services, and implementing enterprise file services.

The project demonstrates core Windows Server administration skills commonly performed by System Administrators, IT Support Specialists, and Infrastructure Engineers.

## Lab Environment

### SERVER1

- Windows Server 2025
- Domain Controller
- DomainX.com
- DNS Server
- Global Catalog
- DFS Namespace Host

### SERVER2

- Windows Server 2025
- Domain Controller
- DomainY.com
- DFS Replication Partner

### MEMBER1

- Windows Server 2025
- Member Server (DomainX.com)

### USER1

- Windows 11 Pro
- Domain-Joined Client

## Technologies Used

- Windows Server 2008
- Windows Server 2016
- Windows Server 2022
- Windows Server 2025
- Windows 11 Pro
- Active Directory Domain Services
- DNS
- Active Directory Users and Computers
- Active Directory Sites and Services
- Active Directory Domains and Trusts
- DFS Namespaces
- DFS Replication
- SMB
- NFS
- NTFS Permissions
- File Server Resource Manager (FSRM)
- Group Policy
- Event Viewer
- PowerShell

## Project Highlights

### Active Directory

- Deployed and configured Active Directory Domain Services
- Created Organizational Units, users, groups, and computer objects
- Raised domain and forest functional levels
- Configured forest trust relationships
- Configured Sites, Subnets, and Site Links
- Configured the Global Catalog
- Enabled the Active Directory Recycle Bin
- Prestaged and administered a Read-Only Domain Controller (RODC)

### File Services

- Configured NTFS permissions
- Enabled file auditing
- Configured SMB and NFS shared folders
- Implemented DFS Namespaces
- Configured DFS Replication
- Implemented File Server Resource Manager (FSRM)
- Configured storage quotas and file screens

## Repository Structure

architecture/
active-directory/
file-services/

## Skills Demonstrated

- Windows Server Administration
- Active Directory Administration
- Identity and Access Management
- Enterprise File Services
- Windows Security
- File System Administration
- Troubleshooting
- PowerShell Administration
