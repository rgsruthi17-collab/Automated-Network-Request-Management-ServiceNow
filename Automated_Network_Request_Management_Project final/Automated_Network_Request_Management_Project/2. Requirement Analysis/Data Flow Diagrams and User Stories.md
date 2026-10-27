# Data Flow Diagrams and User Stories

## High-level data flow
```mermaid
flowchart TD
 A[Employee opens Service Catalog] --> B[Enter network request details]
 B --> C[Submit catalog request]
 C --> D[Flow Designer reads variables]
 D --> E[Create custom table record]
 E --> F[Send notification]
 F --> G[Request approval]
 G --> H{Decision}
 H -->|Approved| I[Update record: Approved]
 H -->|Rejected| J[Update record: Rejected]
```

## User stories
- As an employee, I want a guided catalog form so that I can submit complete request details.
- As a requester, I want user information populated consistently to reduce re-entry.
- As an approver, I want a notification and the ability to approve or reject.
- As support staff, I want request data stored in a dedicated table.
- As a process owner, I want the stored status updated automatically.

## Acceptance criteria
Submitted values are mapped correctly, the custom record is created, notification and approval steps run, and the final status matches the approval outcome.