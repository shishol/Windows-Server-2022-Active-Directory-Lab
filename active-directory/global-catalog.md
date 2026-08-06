# Global Catalog Configuration

## Overview
Configured the Global Catalog to enable forest-wide object searches and support user authentication across multiple Active Directory domains. The Global Catalog stores a partial replica of every object within the forest, allowing users and applications to quickly locate directory information.

## Objective

Configure and validate Global Catalog services within the Active Directory environment.

## Key Functions

### Forest-Wide Searches

The Global Catalog enables users to search for directory objects across all domains within a forest.

### User Authentication

The Global Catalog plays a critical role in user logon processes and Universal Group membership lookups.

### Resource Discovery

Users can locate directory resources without querying every domain individually.

## Validation

- Verified Global Catalog server status
- Confirmed object lookup functionality
- Tested directory search operations

## Skills Demonstrated

- Active Directory Infrastructure Management
- Authentication Services
- Directory Services Administration
- Enterprise Identity Management

## Lab Steps

### 1. Verified Global Catalog Configuration

Opened Active Directory Sites and Services, navigated to the Domain Controller's NTDS Settings, and confirmed that the Global Catalog option was enabled. This allows the Domain Controller to maintain a partial replica of all objects within the forest, supporting authentication and directory searches across domains.

<img width="613" height="433" alt="Screenshot 2026-07-16 071600" src="https://github.com/user-attachments/assets/a7dfe5fe-8edc-4211-9b10-32307638411b" />

### 2. Reviewed Site Configuration

Reviewed the Active Directory Site configuration and verified that Universal Group Membership Caching was enabled for the site. This helps improve authentication performance in remote sites while reducing dependency on constant Global Catalog communication.

<img width="613" height="434" alt="Screenshot 2026-07-16 071632" src="https://github.com/user-attachments/assets/9290fb0f-eb5b-4b0a-b369-653435458fd9" />

