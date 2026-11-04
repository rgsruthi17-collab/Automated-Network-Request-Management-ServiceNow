# Technology Stack

## Platform
**ServiceNow** — platform used to build the request form, store request data, and automate the approval lifecycle.

## Components
| Component | Purpose |
|---|---|
| Service Catalog | Provides the Network Request item and request submission experience |
| Catalog Variables | Capture requester, contact, connection, payment, and address details |
| Variable Set | Reuses user details through a user reference and auto-populated fields |
| Catalog UI Policy | Conditionally displays the Existing ID field |
| Custom Table | Stores the submitted network request information |
| Flow Designer | Orchestrates variable retrieval, record creation, email, approval, decision checking, and record update |
| Approvals | Captures the approver's decision |
| Notifications | Communicates request-related updates through email |

## Platform capabilities used
- Catalog item configuration
- Variable and variable-set configuration
- Conditional form behavior
- Table and field configuration
- Flow Designer actions and data pills
- Approval and email steps
- Flow execution and record verification

## Environment
Development and testing are performed in a ServiceNow instance. Instance release, plugins, exact table schema, and user roles should be documented from the actual environment used for the demonstration.
