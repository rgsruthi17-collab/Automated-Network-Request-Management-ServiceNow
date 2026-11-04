# Proposed Solution

## Solution summary
Create a Network Request item in the ServiceNow Service Catalog and connect it to a Flow Designer flow that manages the request's data and approval lifecycle.

## User journey
1. User opens the Service Portal and selects Network Request.
2. User enters Requested For, mobile number, connection type, applicable Existing ID, amount, payment mode, and address.
3. Reusable user details are populated through the configured variable set.
4. The Catalog UI Policy controls visibility of Existing ID based on the configured condition.
5. User submits the request.
6. Flow Designer retrieves the submitted catalog variables and creates a record in the custom table.
7. The flow sends an email and asks for approval.
8. The flow checks the approval result and updates the custom record.

## Main modules
- Request form and catalog variables
- User-details variable set
- Conditional UI behavior
- Custom request data table
- Flow Designer automation
- Email notification and approval handling

## Expected benefits
- Consistent request information
- Reduced repetitive data entry
- Less manual coordination between request and approval steps
- Centralized request data
- Improved visibility of the approval outcome

## Implementation boundary
This solution automates the request workflow. It does not itself configure routers, switches, network access policies, or physical connectivity.
