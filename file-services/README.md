# File Service Creation and Configuration

This section documents the file services infrastructure implemented within the Windows Server Active Directory Lab environment. My objective was to configure secure file sharing, centralized namespace management, replication, auditing, and storage controls commonly found in enterprise environments.

## Technologies Used

- NTFS Permissions
- SMB File Sharing
- NFS File Sharing
- DFS Namespaces
- DFS Replication
- File Auditing
- File Server Resource Manager (FSRM)
- Storage Quotas
- File Screening

## NTFS Permissions

Configured and tested NTFS permissions to provide granular access control for users and groups within Active Directory.

Key Tasks performed:

- Assigning Permissions to domain users and groups
- Testing inherited and explicit permissions
- Verifying access restrictions
- Implementing the principle of least priviilege

## File Auditing

Enabled auditing policies to track access to sensitive files and folders.

Key Tasks performed:

- Configured Advanced Audit Policy settings
- Enabled object access auditing
- Generated and reviewed audit events
- Verified successful and failed access attempts through Event Viewer

## SMB and NFS Shares

Configured both SMB and NFS shared folders to support access from different systems.

Implemented:

- SMB shared folders with customized share permissions
- NFS shared folders with read/write access
- Access testing from client systems

## DFS Namespace

Implemented a Distributed File System namespace to provide a unified path for shared resources.

Benefits:
- Simplified user access to network resources
- Abstracted physical server locations
- Improved  manageability of shared folders

Example of shared resources:

\DomainX.com\Marketing

## DFS Replication 

Configured DFS Replication between SERVER1 and SERVER2

Validating process included:

- Replicatoin health verification
- File synchronization testing
- Redundancy and availability improvements

## File Server Resource Manager

Configured storage management controls using FSRM.

Implemented:

- User and folder quotas
- File screening policies
- Storage monitoring and reporting

## Security Considerations

The file services infrastructure was desgined with security and availability in mind by implenting:

- Role-based access controls
- File auditing
- Distributed files access
- Replicated shared resources
- Storage governance through quotas and screening











