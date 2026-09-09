# Solution Architecture

```text
User
  |
  v
Service Catalog – Network Request
  |
  v
Get Catalog Variables
  |
  v
Create Record – Custom Database Table
  |
  +----> Send Email
  |
  v
Ask for Approval
  |
  v
If Request is Approved
  |
  +---- Yes ----> Update Record
  |
  +---- No -----> No approval update path
```

## Main Components
- Catalog Item: Network Request
- Variable Set: Network Request User Details
- UI Policy: controls Existing ID visibility
- Database Table: stores request data
- Flow Designer: automates processing
- Approval Request: controls authorization
- Email Notification: informs the requester

## Data Storage
The custom table stores request details and Approval Status, with a Database Number associated with the submitted request.