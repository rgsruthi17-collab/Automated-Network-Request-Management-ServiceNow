# Automated Network Request Management in ServiceNow

## Project Overview

**Automated Network Request Management in ServiceNow** is a ServiceNow-based project that automates the submission, validation, approval, notification, and database update of network connection requests.

The solution uses a Service Catalog item, catalog variables, a reusable variable set, a UI Policy, a custom database table, and Flow Designer automation.

## Key Features

- Network Request catalog item
- Requested For, mobile number, connection type, existing ID, amount, payment mode, and address fields
- Reusable user-details variable set with user reference and auto-populated details
- Conditional display of Existing ID using a Catalog UI Policy
- Custom database table for storing request information
- Automated record creation through Flow Designer
- Email notification step
- Approval workflow
- Automatic update of approval status after approval decision

## Automation Flow

`Service Catalog Request → Get Catalog Variables → Create Record → Send Email → Ask for Approval → Check Approval → Update Record`

## Technology

- ServiceNow Service Catalog
- ServiceNow Flow Designer
- ServiceNow custom tables
- Catalog UI Policies and Variables
- ServiceNow Approvals and Notifications

## Project Documentation

1. [Ideation Phase](Automated_Network_Request_Management_Project/1.%20Ideation%20Phase/README.md)
2. [Requirement Analysis](Automated_Network_Request_Management_Project/2.%20Requirement%20Analysis/README.md)
3. [Project Design Phase](Automated_Network_Request_Management_Project/3.%20Project%20Design%20Phase/README.md)
4. [Project Planning Phase](Automated_Network_Request_Management_Project/4.%20Project%20Planning%20Phase/README.md)
5. [Project Development Phase](Automated_Network_Request_Management_Project/5.%20Project%20Development%20Phase/README.md)
6. [Project Documentation](Automated_Network_Request_Management_Project/6.%20Project%20Documentation/README.md)

## Testing

A test request was submitted through the ServiceNow Service Portal. The request generated a Request and Requested Item, the approval was completed, the custom database record was created, and the Flow Designer test execution completed successfully.

## Conclusion

The project demonstrates how ServiceNow can automate a network-service request lifecycle and reduce manual processing by combining Service Catalog, conditional form behavior, centralized data storage, notifications, approvals, and Flow Designer automation.
