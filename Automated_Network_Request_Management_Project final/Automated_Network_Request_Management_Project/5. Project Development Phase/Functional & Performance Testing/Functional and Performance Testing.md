# Functional and Performance Testing

## Objective
Verify that the catalog form, conditional behavior, data mapping, custom record creation, notification, approval, and status update work as intended.

## Functional test cases
| Test ID | Scenario | Expected result | Evidence to capture |
|---|---|---|---|
| FT-01 | Open Network Request item | Catalog form loads | Catalog item screenshot |
| FT-02 | Populate requester details | Values are captured correctly | Completed form |
| FT-03 | Select connection type requiring Existing ID | Existing ID is displayed according to UI Policy condition | Conditional field screenshot |
| FT-04 | Select a type where Existing ID is not applicable | Existing ID is hidden according to configured condition | Conditional field screenshot |
| FT-05 | Submit a valid request | Request and Requested Item are generated | Request record |
| FT-06 | Run Get Catalog Variables | Flow reads submitted values | Flow execution details |
| FT-07 | Create custom-table record | Record contains mapped values | Custom table record |
| FT-08 | Send email step | Configured notification step executes | Flow execution/email evidence |
| FT-09 | Ask for approval | Approval is created for configured approver | Approval record |
| FT-10 | Approve or reject request | Flow evaluates the decision | Approval and flow evidence |
| FT-11 | Update request record | Stored status reflects decision | Updated custom record |

## Performance and reliability checks
- Observe form load and submission behavior in the test instance.
- Confirm that the flow completes without unexpected errors.
- Check that the custom record is created once for each submitted request.
- Verify that data pills map to the intended fields.
- Review flow execution details and email logs when a step does not behave as expected.

## Recorded project validation
The project README records a successful test submission in which a Request and Requested Item were generated, approval was completed, a custom database record was created, and the Flow Designer test execution completed successfully. Add exact dates, screenshots, durations, and additional outcomes only after checking the instance.

## Test result recording template
| Test ID | Actual result | Pass/Fail | Date | Evidence |
|---|---|---|---|---|
| FT-01 | To be recorded from instance | Pending | — | — |
| FT-05 | To be recorded from instance | Pending | — | — |
| FT-07 | To be recorded from instance | Pending | — | — |
| FT-09 | To be recorded from instance | Pending | — | — |
| FT-11 | To be recorded from instance | Pending | — | — |
