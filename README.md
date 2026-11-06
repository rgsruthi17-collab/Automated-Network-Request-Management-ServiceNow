# Automated Network Request Management in ServiceNow

## Project Overview

The **Automated Network Request Management** project is a ServiceNow-based solution designed to automate the process of submitting, approving, tracking, and managing network-related requests.

The system uses the **Service Catalog, Catalog Variables, Catalog UI Policies, Flow Designer, Approvals, Notifications, and a Custom Table** to provide a structured and automated request-management workflow.

The solution reduces manual effort, improves request visibility, ensures proper approval handling, and maintains centralized records of network requests.

---

## Objectives

- Automate network request submission through the ServiceNow Service Catalog.
- Capture requester and network-related information using catalog variables.
- Apply conditional fields using Catalog UI Policies.
- Automatically create and update network request records.
- Route requests through an approval workflow.
- Send email notifications to relevant users.
- Track request status throughout the process.
- Maintain centralized and structured request records.
- Improve efficiency and reduce manual processing.

---

## Key Features

### Service Catalog
Users can submit network requests through a dedicated Service Catalog item.

### Catalog Variables
The request form collects required information such as requester details, request type, network requirement, and other relevant information.

### Reusable Variable Set
A reusable user-details variable set is used to capture common requester information.

### Catalog UI Policy
Conditional form behaviour is implemented using Catalog UI Policy. For example, the **Existing ID** field can be displayed when it is required based on the selected request type.

### Custom Table
Submitted requests are stored in a custom ServiceNow table for centralized management and tracking.

### Flow Designer Automation
The request process is automated using Flow Designer.

### Approval Management
Requests requiring authorization are automatically sent for approval.

### Email Notification
Email notifications are generated during important stages of the request lifecycle.

### Record Update
The request record is automatically updated based on the approval decision and workflow progress.

---

## Project Workflow

```text
Service Catalog Request
        ↓
Get Catalog Variables
        ↓
Create Network Request Record
        ↓
Send Email Notification
        ↓
Ask for Approval
        ↓
Check Approval Decision
        ↓
Update Record
        ↓
Request Completed / Rejected
```

---

## Technologies Used

- **ServiceNow**
- **Service Catalog**
- **Catalog Variables**
- **Variable Sets**
- **Catalog UI Policy**
- **Custom Tables**
- **Flow Designer**
- **Approval Actions**
- **Email Notifications**
- **ServiceNow Database**
- **JavaScript** for ServiceNow scripting/customization where required

---

## Project Development Phases

### 1. Ideation Phase

This phase focuses on identifying the problem, understanding user needs, generating ideas, and selecting the most suitable solution.

Documents included:

- Brainstorming - Idea Generation - Prioritization
- Define Problem Statements
- Empathy Map Canvas

---

### 2. Requirement Analysis

This phase identifies functional and non-functional requirements and defines the required data flow, user stories, and technology stack.

Documents included:

- Data Flow Diagrams and User Stories
- Solution Requirements
- Technology Stack

---

### 3. Project Design Phase

This phase defines how the proposed ServiceNow solution will address the identified problem.

Documents included:

- Problem - Solution Fit
- Proposed Solution
- Solution Architecture

The architecture explains the interaction between the Service Catalog, catalog variables, custom table, Flow Designer, approval process, notifications, and users.

---

### 4. Project Planning Phase

This phase focuses on planning the implementation and defining the logical sequence of activities required to develop the solution.

Documents included:

- Planning Logic

---

### 5. Project Development Phase

This phase covers implementation and testing of the ServiceNow solution.

The project includes:

- Service Catalog configuration
- Catalog variables
- Variable set
- Catalog UI Policy
- Custom table
- Flow Designer automation
- Approval workflow
- Email notification
- Record update logic
- Functional testing
- Performance-related validation
- User Acceptance Testing

Documents included:

- Functional and Performance Testing
- User Acceptance Testing

---

### 6. Project Documentation

This phase contains the final project documentation, report, evidence checklist, and supporting project details.

Documents included:

- Automated Network Request Management Project Documentation
- Automated Network Request Management Project Report
- Final Project Documentation
- Screenshot Evidence Checklist

---

## Benefits

- Reduces manual network request processing.
- Provides a standardized request form.
- Improves request tracking and visibility.
- Automates approval workflows.
- Reduces processing errors.
- Provides centralized request records.
- Improves communication through automated notifications.
- Makes the network request lifecycle easier to manage.

---

## Expected Outcome

The completed solution provides an automated and structured method for managing network requests in ServiceNow.

Users can submit requests through the Service Catalog, while the system automatically processes the request, creates the required record, sends notifications, obtains approval, checks the approval decision, and updates the request accordingly.

This demonstrates how ServiceNow can be used to automate enterprise request-management processes.

---

## Project Repository Structure

```text
Automated-Network-Request-Management-ServiceNow/
│
├── README.md
│
└── Automated Network Request Management Project/
    │
    ├── 1. Ideation Phase/
    │
    ├── 2. Requirement Analysis/
    │
    ├── 3. Project Design Phase/
    │   ├── Problem - Solution Fit/
    │   ├── Proposed Solution/
    │   └── Solution Architecture/
    │
    ├── 4. Project Planning Phase/
    │
    ├── 5. Project Development Phase/
    │   ├── Functional & Performance Testing/
    │   └── User Acceptance Testing/
    │
    └── 6. Project Documentation/
```

---

## Project Evidence

The project documentation contains supporting screenshots and evidence related to:

- Service Catalog configuration
- Catalog variables
- Variable sets
- Catalog UI Policy
- Custom table
- Flow Designer
- Approval workflow
- Email notifications
- Request records
- Testing activities
- User acceptance testing

Refer to the **Screenshot Evidence Checklist** in the Project Documentation phase for the required evidence.

---

## Conclusion

The **Automated Network Request Management in ServiceNow** project demonstrates the use of ServiceNow automation capabilities to create an efficient network request-management solution.

By combining Service Catalog, Catalog UI Policies, custom tables, Flow Designer, approvals, and notifications, the system provides a structured workflow from request submission to final decision and record update.

The project demonstrates practical knowledge of **ServiceNow application development, workflow automation, service catalog configuration, requirement analysis, system design, testing, and technical documentation**.
