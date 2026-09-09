# 2. Requirement Analysis

## Problem Statement

Manual network-service requests can require repeated data entry, manual approval follow-up, and separate status tracking. The project provides a centralized and automated ServiceNow workflow.

## Existing System

Requests may be communicated manually and tracked across disconnected records, increasing the possibility of delays and inconsistent information.

## Proposed System

A ServiceNow Service Catalog item collects network-request details and Flow Designer automates record creation, notification, approval, and status update.

## Functional Requirements

1. Users can submit a Network Request.
2. The form captures requester, mobile number, connection type, existing ID, total amount, payment mode, and address.
3. Existing ID is conditionally displayed for an Existing connection.
4. User details can be captured through a reusable variable set.
5. A database record is created automatically.
6. An email notification action is included.
7. An approval is requested.
8. The database record is updated after approval.

## Non-Functional Requirements

- Usable and simple request form
- Reliable workflow execution
- Centralized data storage
- Traceable approval status
- Maintainable ServiceNow configuration

## Software Requirements

- ServiceNow Personal Developer Instance
- Service Catalog
- Flow Designer
- Web browser

## Hardware Requirements

- Computer or laptop
- Internet connection
