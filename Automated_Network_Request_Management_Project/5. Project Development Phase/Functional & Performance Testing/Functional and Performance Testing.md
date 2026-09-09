# Functional and Performance Testing

## Functional Test Cases
| Test | Expected Result |
|---|---|
| Open Network Request | Catalog form loads correctly |
| Select New | Existing ID is hidden according to UI Policy |
| Select Existing | Existing ID is available |
| Submit request | Request/RITM is created |
| Flow execution | Variables are retrieved and record is created |
| Email action | Notification action executes |
| Approval | Approval request is generated and can be approved |
| Approved condition | Approved path evaluates true |
| Update Record | Database record is updated |

## Performance Checks
The workflow was tested through Flow Designer execution. Each configured action completed successfully in the test execution, with the final run reaching Complete.