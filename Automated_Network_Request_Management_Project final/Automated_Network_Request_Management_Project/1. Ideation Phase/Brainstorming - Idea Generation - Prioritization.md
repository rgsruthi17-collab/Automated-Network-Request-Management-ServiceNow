# Brainstorming, Idea Generation and Prioritization

## Objective
Identify a practical way to standardize and automate network connection requests using the ServiceNow platform.

## Current pain points
- Request details may arrive through inconsistent channels or formats.
- Missing requester or connection information can delay processing.
- Manual status tracking makes it harder for users to understand progress.
- Approval decisions and notifications can be separated from the request record.
- Re-entering information increases the possibility of errors.

## Ideas considered
1. Use a Service Catalog item as the single request entry point.
2. Use catalog variables to capture structured information.
3. Reuse requester details through a variable set and user reference.
4. Apply a Catalog UI Policy to show Existing ID only when relevant.
5. Store submitted information in a dedicated custom table.
6. Use Flow Designer for record creation, notifications, approval, and status updates.

## Prioritization
| Priority | Idea | Reason |
|---|---|---|
| High | Catalog item and structured variables | Establishes a consistent intake process |
| High | Flow Designer approval and record update | Automates the request lifecycle |
| High | Custom table | Provides a dedicated record for request information |
| Medium | Reusable variable set | Reduces repeated requester data entry |
| Medium | Conditional Existing ID field | Keeps the form relevant to the selected request |
| Medium | Email notification | Keeps stakeholders informed |

## Selected concept
Build a ServiceNow network request catalog experience connected to a Flow Designer workflow and a custom request table.

## Expected outcome
A traceable request process with structured intake, automated processing, approval handling, notifications, and a stored request status.
