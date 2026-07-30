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
