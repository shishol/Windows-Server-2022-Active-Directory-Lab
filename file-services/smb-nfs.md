# SMB and NFS File Sharing

## Objective

Configure and manage SMB and NFS shared folders to support file access across different operating systems and network environments.

## Environment

- Windows Server 2022
- Active Directory Domain
- Server for NFS
- Client for NFS

## SMB Configuration

### Tasks Performed

- Created SMB shared folders
- Configured share permissions
- Configured NTFS permissions
- Tested access from domain-joined systems

### Validation

- Verified user access to shared folders
- Confirmed permission enforcement
- Tested read and write operations

## NFS Configuration

### Tasks Performed

- Installed Server for NFS
- Configured NFS shared folders
- Assigned client access permissions
- Verified connectivity using NFS clients

### Validation

- Confirmed successful NFS share access
- Tested file creation and modification
- Verified access restrictions

## Security Considerations

Access controls were implemented using:

- Share permissions
- NTFS permissions
- Active Directory security groups

These controls ensured users could access only the resources required for their role.

## Skills Demonstrated

- SMB Administration
- NFS Administration
- Cross-Platform File Sharing
- Access Control Configuration
- Windows Server File Services

