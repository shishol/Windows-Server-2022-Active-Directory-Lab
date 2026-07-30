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
