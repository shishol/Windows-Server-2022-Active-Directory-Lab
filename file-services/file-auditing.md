# File Auditing

## Objective

Configure and verify file auditing to monitor access to sensitive files and folders within an Active Directory environment.

## Environment

- Windows Server 2025
- Active Directory Domain Services
- Group Policy
- Event Viewer

## Tasks Performed

- Enabled Audit Object Access through Group Policy
- Configured auditing on shared folders
- Specified successful and failed audit events
- Accessed files using test user accounts
- Reviewed security logs in Event Viewer

## Implementation

File auditing was configured to record user access to selected files and folders. Audit policies were applied through Group Policy, and auditing entries were configured on the target folders to capture successful and failed access attempts.

## Validation

The configuration was verified by:

- Accessing audited folders using different user accounts
- Reviewing Security logs in Event Viewer
- Confirming successful and failed access events were recorded

## Benefits

- Increased visibility into file access
- Improved security monitoring
- Support for compliance and forensic investigations
- Detection of unauthorized access attempts

## Skills Demonstrated

- Windows File Auditing
- Group Policy Administration
- Event Viewer Analysis
- Security Monitoring
- Windows Server Administration
