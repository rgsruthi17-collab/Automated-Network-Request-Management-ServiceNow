# Empathy Map Canvas

## Primary persona: Network service requester

| Dimension | User perspective |
|---|---|
| Says | “I need a network connection and want to know what information is required.” |
| Thinks | “Has my request been submitted? Who needs to approve it?” |
| Does | Opens the Service Portal, completes the catalog form, submits the request, and checks for updates. |
| Feels | Wants the process to be simple, predictable, and transparent. |

## Needs
- One clear place to submit a network request.
- Simple fields with understandable labels.
- Requester details that do not need to be repeatedly entered.
- Conditional fields that appear only when applicable.
- Confirmation and progress updates.

## Pain points
- Unclear or incomplete request forms.
- Repeated entry of the same personal details.
- Uncertainty about approval progress.
- Lack of a single record containing request information and status.

## Design opportunities
- Use a Service Catalog item with structured variables.
- Reuse user details through a variable set.
- Use a Catalog UI Policy for conditional field visibility.
- Automate notifications and approval with Flow Designer.
- Store request details in a custom table for traceability.

*Persona statements are design assumptions for the project and should be validated with actual users where possible.*
