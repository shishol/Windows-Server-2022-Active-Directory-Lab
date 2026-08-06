# Forest Trusts

## Objective

Configure and validate trust relationships between two separate Active Directory forests to enable authentication and resource access across organizational boundaries.

## Environment

### Forest 1

- DomainX.com

### Forest 2

- DomainY.com

## Tasks Performed

- Created a trust relationship between DomainX.com and DomainY.com
- Configured DNS name resolution between forests
- Verified trust functionality
- Tested cross-forest authentication
- Examined trust properties and available trust options

## Implementation

A forest trust was established to allow users from one forest to authenticate and access resources located in the other forest.

The trust configuration required proper DNS resolution and communication between domain controllers in each forest.

## Validation

The following tests were performed:

- Verified trust status through Active Directory Domains and Trusts
- Confirmed successful name resolution between forests
- Tested user authentication across forests
- Validated resource access permissions

## Skills Demonstrated

- Active Directory Forest Administration
- Trust Relationship Configuration
- Cross-Forest Authentication
- DNS Troubleshooting
- Identity and Access Management

## Lab Steps

### 1. DNS Configuration 

Before creating trust between the two domains, I added DomainY.com as a Conditional Forwarder within SERVER1's DNS Manager and vice versa.

<img width="524" height="364" alt="Screenshot 2026-07-15 211338" src="https://github.com/user-attachments/assets/0ca7febb-97df-4e1d-b4a1-35dbbc274574" />

### 2. Trust

Configured the trust type as "Forest trust" and selected both specified domains within sides of trust. Authentication level was also configured.

<img width="348" height="278" alt="Screenshot 2026-07-15 211644" src="https://github.com/user-attachments/assets/a92e5c9a-07c1-4dfd-8f65-3290928ccc23" />
<img width="351" height="279" alt="Screenshot 2026-07-15 211712" src="https://github.com/user-attachments/assets/141d2fbb-bfed-4d48-9c40-4d2495b82c2f" />


### 3. Confirmation and verification

Within domainX's properties, I was able to verify the trust type and whether the trust was transitive for both domainX.com and domainY.com. I also verified whether the trust was transferred onto domainY or not.

<img width="284" height="321" alt="Screenshot 2026-07-15 213517" src="https://github.com/user-attachments/assets/135bde53-9b1e-48b5-b33a-ef85a589d5e8" />
<img width="284" height="321" alt="Screenshot 2026-07-15 213517" src="https://github.com/user-attachments/assets/08b804fc-1a22-45f5-b1b0-a5d344d5d650" />
<img width="604" height="416" alt="Screenshot 2026-07-15 213621" src="https://github.com/user-attachments/assets/f83daa75-592c-4c0f-bd70-ae9dffe357c2" />

