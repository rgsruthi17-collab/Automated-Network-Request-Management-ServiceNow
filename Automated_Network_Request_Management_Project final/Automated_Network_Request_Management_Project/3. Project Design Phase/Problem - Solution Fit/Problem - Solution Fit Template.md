# Problem - Solution Fit

## Problem
Network requests need a consistent intake process, complete information, a review/approval step, and a reliable way to track the outcome.

## Proposed fit
A ServiceNow Service Catalog item provides structured intake. Catalog variables and a reusable variable set capture information; a Catalog UI Policy controls conditional visibility; a custom table stores request data; and Flow Designer automates record creation, notification, approval, and status update.

## Fit assessment
| User need | Design response | Benefit |
|---|---|---|
| Standard request entry | Service Catalog item | Consistent submission |
| Requester information | User reference and variable set | Reusable details |
| Relevant form fields | Catalog UI Policy | Reduced unnecessary input |
| Persistent request data | Custom table | Centralized record |
| Timely communication | Email step | Stakeholder awareness |
| Review and decision | Approval action | Formal decision point |
| Traceable outcome | Update record step | Status visibility |

## Risks and mitigations
- **Incorrect field mapping:** verify each catalog variable against its target table field.
- **Missing approval configuration:** validate approver selection and test both outcomes.
- **Notification delivery issues:** check notification settings, recipients, and email logs.
- **Access restrictions:** test with intended requester and approver roles.
- **Unclear scope:** keep real network provisioning outside the documented solution unless an integration is actually implemented.

## Conclusion
The selected design addresses the project's request intake and approval-tracking needs using native ServiceNow capabilities.
