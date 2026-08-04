# Organizational Units

## Objective

Create and manage Organizational Units (OUs) and Active Directory objects to organize resources and simplify administrative management.

## Environment

- Windows Server 2025
- Active Directory Domain Services
- DomainX.com

## Tasks Performed

- Created Organizational Units (OUs)
- Created user accounts
- Created security groups
- Created computer objects
- Moved objects into the appropriate Organizational Units
- Managed object properties using Active Directory Users and Computers

## Implementation

Organizational Units were created to logically separate users, computers, and groups within the domain. This structure improves administration by allowing resources to be organized based on department, function, or location.

User, group, and computer objects were created within their respective OUs to simulate an enterprise Active Directory environment.

## Benefits

- Simplified Active Directory administration
- Improved organization of directory objects
- Easier delegation of administrative tasks
- Better scalability for future growth

## Skills Demonstrated

- Organizational Unit Management
- User and Group Administration
- Computer Object Management
- Active Directory Users and Computers (ADUC)
- Active Directory Administration

## Lab Steps

### 1. Created multiple security groups to organize separate marketing groups for a streamlined administration process.

Created the following:

- Marketing
- Marketing-G
- Marketing-U

<img width="609" height="427" alt="Screenshot 2026-07-16 071925" src="https://github.com/user-attachments/assets/91cda058-050a-40e5-9c02-e95a39c49393" />

### 2. Created a template purposed for easier user creation in large organizations. Enabled "change at next logon" to make sure each new user sets a unique password after they receive their account.

Created the following under "domainX.com/Marketing":

- Marketing Template

<img width="614" height="424" alt="Screenshot 2026-07-16 072507" src="https://github.com/user-attachments/assets/b21cc882-5afd-48f6-8f7f-fd44c855cabd" />

### 3. Configured "Marketing Template" to be a member of "Domain Users" of domainX.com and "Marketing-G".

<img width="612" height="467" alt="Screenshot 2026-07-16 072726" src="https://github.com/user-attachments/assets/7482508b-1f24-4331-ac43-4bd676442b68" />

### 4. Created user from "Marketing Template"

Created user accounts for the following new hires:

- Bob Burtt
- Mary Stewart
- John Lavigne

Created a computer object to assign permissions to a new office PC:

- MKTG-PC-01

<img width="615" height="426" alt="Screenshot 2026-07-16 073236" src="https://github.com/user-attachments/assets/03398a3b-472b-4af8-93eb-4f9c05efb90a" />








