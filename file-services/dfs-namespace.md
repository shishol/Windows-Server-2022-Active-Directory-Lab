# DFS Namespaces

## Objective

Configure a Distributed File System (DFS) Namespace to provide users with a centralized and consistent location for shared resources.

## Environment

- Windows Server 2025
- Active Directory Domain Services
- SERVER1
- SERVER2
- DFS Namespace

## Tasks Performed

- Installed the DFS Namespace role service
- Created a domain-based DFS Namespace
- Added shared folders to the namespace
- Configured namespace folders for MarketingMaterials and MarketingTemplates
- Verified client access through the namespace

## Implementation

A domain-based DFS Namespace was created to provide users with a single logical path to shared resources, regardless of their physical server location.

The MarketingMaterials and MarketingTemplates shared folders were added to the namespace to simplify user access and administration.

Example namespace path:

\DomainX.com\Marketing

## Validation

Testing included:

- Browsing the DFS Namespace
- Opening shared folders through the namespace
- Confirming access to namespace targets
- Verifying namespace functionality after configuration

## Benefits

- Centralized access to shared resources
- Simplified file server management
- Reduced dependency on physical server names
- Improved scalability for enterprise environments

## Skills Demonstrated

- DFS Namespace Administration
- Windows File Services
- Active Directory Integration
- Enterprise File Sharing
