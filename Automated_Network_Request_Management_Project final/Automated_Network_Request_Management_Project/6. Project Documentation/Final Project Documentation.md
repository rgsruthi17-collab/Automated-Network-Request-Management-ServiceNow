# Final Project Documentation
## Automated Network Request Management in ServiceNow

### Abstract
This project configures a ServiceNow workflow for submitting, storing, notifying, approving, and updating network-service requests. It combines Service Catalog, catalog variables, UI Policies, a custom table, and Flow Designer.

### 1. Introduction
Organizations need a consistent process for receiving and reviewing network-service requests. Unstructured intake and manual follow-up can make information incomplete and status tracking difficult.

### 2. Problem definition
The process needs a standardized form, reliable storage of submitted values, clear approval handling, and a consistent status after a decision.

### 3. Objectives
- Standardize request intake.
- Reduce repeated entry through reusable user details.
- Display conditional fields based on request choices.
- Store request data in a custom table.
- Automate notifications and approvals.
- Update the record after the decision.

### 4. Requirements
The catalog item captures requester and contact details, connection type, applicable existing ID, amount, payment mode, and address. The workflow requires a custom table, Flow Designer, notifications, and an approval mechanism.

### 5. System design
The Service Portal catalog form is the presentation layer. Catalog variables and UI Policy govern input behavior. Flow Designer orchestrates processing. The custom table stores project-specific request data, while platform request records retain the catalog transaction.

### 6. Workflow
1. Employee submits the catalog item.
2. Flow retrieves catalog variables.
3. Flow creates the custom record.
4. Notification action runs.
5. Approval is requested.
6. The decision is evaluated.
7. The custom record is updated.

### 7. Testing
Test required fields, conditional visibility, submission, mapping, record creation, notification, approval, rejection, and error handling. Retain genuine instance evidence and record actual outcomes.

### 8. Limitations
The solution automates request administration but does not itself provision network infrastructure. Production deployment requires review of access controls, approval rules, data retention, and operational ownership.

### 9. Future scope
Potential improvements include SLA timers, escalation, dashboards, automated reminders, provisioning integrations, and audit reporting.

### 10. Conclusion
Native ServiceNow configuration can standardize request intake and automate key lifecycle steps. Reliable operation depends on accurate mappings, appropriate permissions, and testing of both approval outcomes.