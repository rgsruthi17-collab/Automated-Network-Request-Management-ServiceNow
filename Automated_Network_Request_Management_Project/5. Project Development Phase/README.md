# 5. Project Development Phase

## 5.1 Catalog Item

Created a Service Catalog item named **Network Request** under the Network category.

## 5.2 Variables

Configured variables for Requested For, Mobile Number, Type of Connection, Existing ID, Total Amount, Mode of Payment, and Address.

## 5.3 Variable Set

Created **Network Request User Details** containing Opened on behalf of, Email ID, User Name, and Phone Number. User details are designed for reuse and auto-population.

## 5.4 UI Policy

Configured a Catalog UI Policy for the condition **Type of Connection is Existing** so the Existing ID field is shown only when applicable.

## 5.5 Database Table

Created a custom Database Table to store submitted network-request information. Important fields include Database Number, Requested For, Mobile number, Address, Total Amount, Mode of Payment, Type of Connection, and Approval Status.

## 5.6 Flow Designer

The automation flow contains:

1. Service Catalog trigger
2. Get Catalog Variables
3. Create Record
4. Send Email
5. Ask for Approval
6. If Request is Approved
7. Update Record

The Create Record action maps catalog values into the custom Database Table and initially records the approval status as Requested.

## 5.7 Testing

A real ServiceNow request was submitted through the Service Portal. The request and Requested Item were generated, an approval was completed, the custom database record was created, and the Flow Designer test execution reached the Complete state.

## 5.8 QA Evidence

Recommended screenshots for this phase:

- Network Request catalog form
- New/Existing connection behavior
- Variable Set configuration
- Custom Database Table record
- Flow Designer canvas
- Approval result
- Flow Designer test execution
