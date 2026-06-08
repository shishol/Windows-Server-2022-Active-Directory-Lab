# Windows Sever 2022 Active Directory Lab

My process of designing and impltementing a multi-server, multi-forest, Active Directory environment using Windows Server to simulate infrastructure management.

## Key Technologies:

- Active Directory Domain Services
- DNS
- DFS Namespace
- DFS Replication
- SMB
- NFS
- NTFS Permissions
- File Auditing
- PowerShell
- Read-Only Domain Controllers

## Lab Environment

### Active Directory Infrastructure/Forests

Forest 1: DomainX.com

Forest 2: DomainY.com

### Servers

**SERVER1**
- Domain Controller for DomainX.com
- Root Forest Domain Controller
- DNS Server
- DFS Namespace Host

**SERVER2**
- Domain Controller for DomainY.com
- Member Server
- DFS Replication Partner

### Trust Relationships

- Configured bidirectional forest trust between DomainX.com and DomainY.com
- Verified cross-forest authentication and resource access

## Skills Demonstrated

### Active Directory

- Installed and configured AD DS
- Raised forest and domain functional levels
- Created and managed Organizational Units
- Managed users, groups, and computer objects
- Configured Global Catalog services
- Configured Sites and Services
- Created subnet and site-link objects
- Enabled Active Directory Recycle Bin
- Restored deleted directory objects

### Identity and Authentication

- Configured inter-forest trust relationships
- Managed Read-Only Domain Controllers (RODCs)
- Configured password replication policies

### File Services

- Configured NTFS permissions
- Implemented SMB shares
- Implemented NFS shares
- Configured DFS Namespaces
- Configured DFS Replication

### Security

- Implemented file auditing
- Configured user and folder quotas
- Created file screens using FSRM

### Automation

- Used PowerShell for Active Directory administration
- Automated common administrative tasks
