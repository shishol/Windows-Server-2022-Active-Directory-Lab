# Storage Quotas and File Screens

## Objective

Configure File Server Resource Manager (FSRM) to control storage usage and restrict unauthorized file types.

## Environment

- Windows Server 2025
- File Server Resource Manager (FSRM)
- Active Directory Domain Services

## Tasks Performed

- Installed File Server Resource Manager
- Configured user and folder quotas
- Created quota templates
- Configured file screening policies
- Tested quota enforcement
- Verified blocked file types

## Implementation

FSRM was configured to manage storage allocation and enforce file screening policies.

Quota templates were applied to monitor and limit storage usage, while file screens were created to prevent users from storing unauthorized file types on shared resources.

## Validation

Testing included:

- Exceeding configured storage quotas
- Attempting to save blocked file types
- Confirming quota and file screen enforcement
- Reviewing FSRM notifications and reports

## Benefits

- Prevented excessive storage consumption
- Improved storage management
- Restricted unauthorized file types
- Supported organizational storage policies

## Skills Demonstrated

- File Server Resource Manager
- Storage Quota Management
- File Screening
- Windows Server Administration
- Enterprise Storage Management
