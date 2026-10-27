# Solution Architecture

## Architecture layers
- **Presentation:** Service Portal and Service Catalog form.
- **Input configuration:** catalog variables, reusable variable set, and UI Policy.
- **Orchestration:** Flow Designer.
- **Data:** custom network-request table and platform request records.
- **Communication and decision:** email notification and approval action.

## Workflow sequence
1. Employee submits the catalog item.
2. Flow retrieves catalog variables.
3. Flow creates a record in the custom table.
4. Notification action runs.
5. Approval is requested.
6. The approval outcome is evaluated.
7. The custom record is updated.

## Design considerations
Use stable field mappings, least-privilege access, meaningful status values, and execution logs to diagnose failures.