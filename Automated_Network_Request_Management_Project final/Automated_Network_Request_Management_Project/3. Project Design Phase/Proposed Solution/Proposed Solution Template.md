# Proposed Solution

## Overview
Use ServiceNow's native request and workflow capabilities to manage network-service requests from submission through approval.

## Main components
1. Service Catalog item with request variables.
2. Reusable user-details variable set.
3. Catalog UI Policy for conditional field visibility.
4. Custom table for request details and status.
5. Flow Designer for record creation, notification, approval, and update.

## Process
```mermaid
flowchart LR
 A[Catalog form] --> B[Submit]
 B --> C[Read variables]
 C --> D[Create custom record]
 D --> E[Notify]
 E --> F[Approval]
 F --> G[Update status]
```

## Expected outcome
A consistent request lifecycle with less manual coordination and a persistent record of request and approval result.