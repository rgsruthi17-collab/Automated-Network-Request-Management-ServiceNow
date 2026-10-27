# Functional and Performance Testing

| ID | Scenario | Expected result |
|---|---|---|
| FT-01 | Open catalog item | Form and required fields display |
| FT-02 | Choose type requiring Existing ID | Existing ID displays as configured |
| FT-03 | Choose type not requiring Existing ID | Existing ID hides as configured |
| FT-04 | Submit valid request | Request submits successfully |
| FT-05 | Trigger Flow Designer | Flow retrieves variables |
| FT-06 | Create custom record | Mapped values are stored |
| FT-07 | Run notification step | Configured notification executes |
| FT-08 | Approve request | Status becomes Approved |
| FT-09 | Reject request | Status becomes Rejected |
| FT-10 | Omit required data | Validation prevents invalid submission |

## Performance observations
Check form loading and submission against normal instance response times. Record measured timings during actual testing rather than assuming performance values.

## Evidence
Capture the catalog form, created record, approval decision, and Flow Designer execution details if available.