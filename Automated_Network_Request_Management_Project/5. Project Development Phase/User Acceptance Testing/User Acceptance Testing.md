# User Acceptance Testing

## Acceptance Scenario
A requester submits a Network Request with the required information. The system creates the request and corresponding database record, sends the configured notification, starts approval and updates the record after approval.

## Acceptance Criteria
- Request form is usable.
- Required request information is captured.
- Existing ID behavior follows the connection type.
- Database record is created.
- Approval status can be tracked.
- Approved requests reach the approved update path.
- Notification action is configured.

## Result
The implemented scenario was exercised using a real request and a Flow Designer test execution. The approval was recorded as Approved and the flow test completed.