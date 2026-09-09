# Data Flow Diagrams and User Stories

## High-Level Data Flow
Requester → Network Request Catalog Item → Get Catalog Variables → Database Table Record → Email Notification → Approval → Approved Condition → Update Record.

## User Stories
- As a requester, I want to submit a network request through a structured form.
- As a requester, I want confirmation that my request was received.
- As an approver, I want to review and approve a request.
- As an administrator, I want request data stored in a centralized table.
- As a team member, I want the record status updated after approval.

## Main Data
Requested For, Mobile Number, Type of Connection, Existing ID, Total Amount, Mode of Payment and Address.