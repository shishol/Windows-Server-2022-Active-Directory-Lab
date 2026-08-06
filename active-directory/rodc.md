# Read-Only Domain Controller (RODC)

## Objective

Configure and manage a Read-Only Domain Controller (RODC) computer account by prestaging the account, configuring Password Replication Policies, and examining credential caching and administrative options.

## Environment

- Windows Server 2025
- Active Directory Domain Services (AD DS)
- SERVER1 (DomainX.com)
- ParisSite
- Active Directory Users and Computers
- Active Directory Sites and Services

## Tasks Performed

- Prestaged an RODC computer account
- Configured the RODC within ParisSite
- Examined Password Replication Policies
- Allowed selected credentials to be cached
- Reviewed RODC account deletion options

## Implementation

A Read-Only Domain Controller was deployed to simulate a branch office environment where physical security may be limited.
Unlike a writable domain controller, the RODC maintains a read-only copy of the Active Directory database and can selectively cache user credentials.

## Password Replication Policy

Password Replication Policies were reviewed and configured to control which user credentials could be stored locally on the RODC.

Benefits include:

- Reduced exposure of sensitive credentials
- Improved branch office security
- Local authentication when WAN connectivity is unavailable

## Validation

- Verified successful RODC deployment
- Confirmed password caching functionality
- Examined credential replication settings
- Reviewed RODC management options

## Security Benefits

- Read-only Active Directory database
- Reduced attack surface
- Controlled credential caching
- Enhanced security for remote locations

## Skills Demonstrated

- Active Directory Domain Services
- Branch Office Administration
- Identity Security
- Password Replication Policies
- RODC Deployment and Management

## Lab Steps

### 1. Pre-Staged the RODC Computer Account

After creating the sites in "sites-and-services.md" I configured a pre-staged Read-Only Domain Controller within "ParisSite"

<img width="613" height="432" alt="Screenshot 2026-07-16 073654" src="https://github.com/user-attachments/assets/b0d61099-7dcf-4eee-8786-48740c958363" />
<img width="407" height="394" alt="Screenshot 2026-07-16 073707" src="https://github.com/user-attachments/assets/53678904-1c85-448a-800e-e685a53c88a8" />
<img width="408" height="396" alt="Screenshot 2026-07-16 073736" src="https://github.com/user-attachments/assets/87090e09-922c-4080-a8cf-6528dda2194c" />

### 2. Domain Controller options

After selecting Read-Only Domain Controller, the DNS Server option was also selected.

<img width="613" height="428" alt="Screenshot 2026-07-16 074447" src="https://github.com/user-attachments/assets/c289660f-bc65-4be0-8d76-f0bdca7dff28" />


### 3. Configured Password Replication Policy

Reviewed and verified which accounts were allowed to cache passwords.

<img width="614" height="429" alt="Screenshot 2026-07-16 074641" src="https://github.com/user-attachments/assets/e017618a-420b-439d-8b33-60526de1c2b7" />
