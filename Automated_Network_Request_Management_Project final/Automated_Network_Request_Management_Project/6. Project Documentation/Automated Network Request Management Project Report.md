# Automated Network Request Management Project Report

## 1. Introduction
Organizations need a reliable way to receive and process internal network-service requests. This project uses ServiceNow to structure request intake and automate key workflow steps.

## 2. Problem definition
Unstructured request information, repeated data entry, manual notifications, and disconnected approval tracking can slow processing and make request status difficult to follow.

## 3. Objectives
Create a standard request form, capture requester and connection details, store submitted information, initiate notification and approval, and update the request record after the decision.

## 4. Proposed system
A Service Catalog item is the user entry point. Catalog variables and a reusable user-details variable set collect information. A Catalog UI Policy conditionally displays Existing ID. Flow Designer handles data retrieval, custom record creation, email notification, approval, decision checking, and record update.

## 5. Implementation components
- Network Request catalog item
- Requested For, mobile number, connection type, Existing ID, amount, payment mode, and address
- Reusable user-details variable set
- Catalog UI Policy
- Custom database table
- Flow Designer
- Approval and email notification steps

## 6. Testing
The project notes report a test submission that generated a Request and Requested Item, completed the approval, created the custom database record, and completed the Flow Designer test execution. Refer to the testing phase for test cases and add the actual screenshots and execution details from the instance.

## 7. Conclusion
The solution demonstrates how native ServiceNow components can be combined to automate a network request lifecycle and improve consistency and traceability.

## 8. Future scope
Reporting, additional exception handling, expanded UAT, and integration with actual network provisioning systems may be considered as future work.
