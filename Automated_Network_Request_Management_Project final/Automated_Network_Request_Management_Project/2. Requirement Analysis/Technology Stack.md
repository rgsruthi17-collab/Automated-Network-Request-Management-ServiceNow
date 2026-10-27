# Technology Stack

| Component | Purpose |
|---|---|
| ServiceNow Service Catalog | Request entry point |
| Catalog Variables | Capture request-specific data |
| Reusable Variable Set | Reuse requester details |
| Catalog UI Policy | Conditionally display fields |
| Custom Table | Persist request details and status |
| Flow Designer | Orchestrate the workflow |
| Approvals | Capture approval decisions |
| Notifications | Inform relevant stakeholders |
| Service Portal | Requester-facing experience |

The solution is configured primarily on the ServiceNow platform. Flow Designer maps catalog variables to the custom table and coordinates notification, approval, and status-update actions.