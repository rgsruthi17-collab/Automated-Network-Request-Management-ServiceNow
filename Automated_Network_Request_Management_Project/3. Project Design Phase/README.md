# 3. Project Design Phase

## System Architecture

The solution is organized into four main layers:

1. **User Interface** – ServiceNow Service Portal and Network Request catalog item.
2. **Form Logic** – Catalog variables, variable set, and UI Policy.
3. **Automation** – Flow Designer retrieves variables, creates a record, sends notification, requests approval, evaluates the result, and updates the record.
4. **Data Layer** – Custom Database Table stores network request information and approval status.

## Request Workflow

`User → Network Request Form → Service Catalog Trigger → Get Catalog Variables → Create Record → Email → Approval → Approval Decision → Update Record`

## Catalog Item Design

Catalog Item: **Network Request**

Variables:
- Requested For
- Mobile Number
- Type of Connection
- Enter your Existing ID
- Total Amount
- Mode of Payment
- Address

## Variable Set

**Network Request User Details**

- Opened on behalf of – Reference to User
- Email ID
- User Name
- Phone Number

## UI Policy

Condition: **Type of Connection is Existing**.

Action: Show **Enter your Existing ID** when Existing is selected; keep it hidden for a New connection.

## Database Design

The custom Database Table stores address, mobile number, payment mode, requested-for reference, total amount, connection type, database number, and approval status.

## Approval Design

The flow waits for an approval decision. When the request is approved, the flow evaluates the approval path and updates the stored record.
