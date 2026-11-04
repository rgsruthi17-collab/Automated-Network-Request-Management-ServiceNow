# Automated Network Request Management in ServiceNow

A structured project repository for designing, configuring, testing, and documenting a network-service request workflow on the ServiceNow platform.

## Project at a glance
The solution lets a user submit a network connection request through the Service Catalog. Catalog variables capture request details; a reusable user-details variable set supports consistent requester information; a Catalog UI Policy conditionally displays the Existing ID field; Flow Designer creates a record in a custom table, sends an email, requests approval, evaluates the decision, and updates the stored approval status.

## Main capabilities
- Service Catalog item for network requests
- Requester and contact details, connection type, existing ID, amount, payment mode, and address
- Reusable user-details variable set with a user reference and auto-populated details
- Conditional Existing ID field using a Catalog UI Policy
- Custom table for request information
- Flow Designer automation for record creation, email notification, approval, decision handling, and record update

## Workflow
`Service Catalog Request → Get Catalog Variables → Create Record → Send Email → Ask for Approval → Check Approval → Update Record`

## Project phases
1. [Ideation Phase](1.%20Ideation%20Phase/README.md)
2. [Requirement Analysis](2.%20Requirement%20Analysis/README.md)
3. [Project Design Phase](3.%20Project%20Design%20Phase/README.md)
4. [Project Planning Phase](4.%20Project%20Planning%20Phase/README.md)
5. [Project Development Phase](5.%20Project%20Development%20Phase/README.md)
6. [Project Documentation](6.%20Project%20Documentation/README.md)

## Platform and tools
ServiceNow Service Catalog, catalog variables and variable sets, Catalog UI Policies, custom tables, Flow Designer, approvals, and notifications.

## Validation status
The project notes record a test request submitted through the ServiceNow Service Portal. A Request and Requested Item were generated, the approval was completed, a custom database record was created, and the Flow Designer test execution completed successfully. Detailed test scenarios and evidence checklist are maintained in Phase 5 and Phase 6.

## Repository guide
All project documents are in the six numbered phase folders. Replace any illustrative or pending evidence with screenshots and outputs from your own ServiceNow instance before final submission.
