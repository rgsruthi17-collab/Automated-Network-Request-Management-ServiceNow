# Final Project Documentation

## Project title
**Automated Network Request Management in ServiceNow**

## 1. Overview
This project automates the submission and approval workflow for network connection requests using ServiceNow.

## 2. Problem statement
A request process that relies on inconsistent forms and manual follow-up can result in missing information, duplicated effort, and limited visibility into approval status.

## 3. Objectives
1. Standardize network request submission.
2. Capture requester and connection details.
3. Reuse user information where possible.
4. Apply conditional form behavior.
5. Store submitted values in a custom table.
6. Automate notification and approval.
7. Update the record with the approval outcome.

## 4. Scope
Included: Service Catalog intake, catalog variables, user-details variable set, Catalog UI Policy, custom-table record creation, email step, approval, decision check, and record update.

Not included: direct router/switch configuration, live network provisioning, and integrations not implemented in the project.

## 5. System workflow
```text
Requester
  ↓
Service Portal / Network Request catalog item
  ↓
Catalog variables and user-details variable set
  ↓
Catalog UI Policy (conditional Existing ID)
  ↓
Flow Designer
  ↓
Get Catalog Variables
  ↓
Create custom-table record
  ↓
Send email
  ↓
Ask for approval
  ↓
Check approval
  ↓
Update custom-table record
```

## 6. Data captured
Requested For, mobile number, connection type, Existing ID (conditional), amount, payment mode, and address. The exact variable and column names should be copied from the implemented instance.

## 7. Testing and validation
The recorded project test generated a Request and Requested Item, completed approval, created the custom database record, and completed Flow Designer execution. Keep screenshots of the catalog form, request, flow execution, approval, and custom record with the final submission.

## 8. Results
The implemented workflow demonstrates structured request intake and automated approval processing. Do not add numerical performance claims unless measured.

## 9. Limitations
The workflow automates request administration and approval. It does not directly provision network connectivity.

## 10. Future enhancements
Dashboards, SLA tracking, richer error handling, more UAT coverage, and integration with network management tools.

## 11. Conclusion
The project demonstrates practical use of ServiceNow Service Catalog, catalog configuration, custom tables, approvals, notifications, and Flow Designer to create a traceable network request process.
