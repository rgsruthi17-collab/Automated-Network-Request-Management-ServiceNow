# Automated Network Request Management Project Report

## Abstract
This project implements an automated network request process in ServiceNow. The solution uses a catalog form for input and Flow Designer for processing, notification, approval and record update.

## Objectives
- Standardize network request submission.
- Reduce manual processing.
- Store request information centrally.
- Provide approval tracking.
- Improve requester communication.

## Implementation
A Network Request Catalog Item was configured with request variables. A reusable variable set captures user details. A UI Policy manages the Existing ID field. Flow Designer retrieves variables, creates a database record, sends email, requests approval and updates the record when approved.

## Testing
The implementation was validated through a real request and Flow Designer test execution.