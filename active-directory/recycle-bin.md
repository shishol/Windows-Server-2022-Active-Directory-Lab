# Active Directory Recycle Bin

## Objective

Enable the Active Directory Recycle Bin feature and recover deleted directory objects without requiring an authoritative restore.

## Environment

- Windows Server 2025
- Active Directory Domain Services
- DomainX.com
- Active Directory Administrative Center

## Tasks Performed

- Enabled the Active Directory Recycle Bin
- Deleted a user object
- Restored the deleted object
- Verified the restored account retained its original attributes

## Implementation

The Active Directory Recycle Bin was enabled at the forest level to provide a simplified recovery method for accidentally deleted directory objects.

A user account was intentionally deleted and successfully restored using the Active Directory Administrative Center, demonstrating object recovery without restoring from backup.

## Benefits

- Rapid recovery of deleted objects
- Preservation of object attributes and group memberships
- Reduced administrative downtime
- Improved disaster recovery capabilities

## Skills Demonstrated

- Active Directory Administrative Center
- Active Directory Recovery
- Forest Feature Management
- User Object Restoration
- Disaster Recovery Administration
