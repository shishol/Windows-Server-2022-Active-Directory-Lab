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

## Lab Steps

### 1. Enabled Active Directory Recycle Bin

Within Active Directory Administrative Center, "Enable Recycle Bin" can be found for the specific forest you'd like to deploy it in.

<img width="1155" height="576" alt="Screenshot 2026-07-16 073412" src="https://github.com/user-attachments/assets/b9a5d0c9-29cc-4c9a-af14-3de68064b6de" />

### 2. Verify Through a Test Object

Deleted a test user to simulate an accidental deletion.

<img width="1158" height="604" alt="Screenshot 2026-07-16 073441" src="https://github.com/user-attachments/assets/5e048b5b-9bfb-4dae-92ae-95e4e9a3fb16" />

### 3. Restoring the forementioned Object

Using the Recycle Bin within Active Directory Administrative Center (ADAC), I was able to recover the deleted user and made sure that it still had the group memberships that were originally attached.

<img width="1159" height="605" alt="Screenshot 2026-07-16 073516" src="https://github.com/user-attachments/assets/e127397d-f3f9-4ff9-aee5-17c0c17a33b6" />

### 4. Confirm Recovery

Verified the restored object appeared in Active Directory Users and Computers

<img width="1158" height="607" alt="Screenshot 2026-07-16 073527" src="https://github.com/user-attachments/assets/da36edc1-91fe-4aa8-8f56-5f639be0cff0" />
