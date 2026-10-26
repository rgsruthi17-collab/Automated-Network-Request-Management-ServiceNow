# Screenshot Evidence Checklist

Use this checklist to complete the visual evidence for the final project report. Capture the screenshots from the actual ServiceNow instance; do not use illustrative mockups as proof that a feature was implemented.

- [ ] **Figure 3 — Network Request catalog form:** show the catalog item and its visible fields.
- [ ] **Figure 4 — Catalog variables / variable set:** show the request variables or the Network Request User Details variable set.
- [ ] **Figure 5 — Catalog UI Policy:** show the condition that controls Existing ID visibility.
- [ ] **Figure 6 — Custom table record:** show a test request record with non-sensitive sample data.
- [ ] **Figure 7 — Flow Designer canvas:** show the workflow actions in sequence.
- [ ] **Figure 8 — Flow execution details:** show the execution for the test request.
- [ ] **Figure 9 — Approval record:** show the approval state and decision.
- [ ] **Figure 10 — Notification evidence:** show the configured notification action or a test email, if available.

## How to add them

1. Create a folder named `screenshots` in this documentation folder.
2. Save screenshots using clear names, for example `catalog-form.png`, `ui-policy.png`, `custom-table-record.png`, `flow-designer.png`, `flow-execution.png`, and `approval-record.png`.
3. Add each image to the report using Markdown, for example:

   `![Figure 3. Network Request catalog form](screenshots/catalog-form.png)`

4. Add a short caption immediately below each image.
5. Blur or hide names, phone numbers, addresses, email addresses, tokens, passwords and other sensitive details before committing images.
6. Only describe a test as **Passed** when the screenshot or actual instance confirms the expected result.

The diagrams in the final report explain the intended workflow; they are not screenshots of the live ServiceNow interface.
