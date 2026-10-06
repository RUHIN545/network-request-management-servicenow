# Automated Network Request Management in ServiceNow

A ServiceNow solution that lets employees raise network requests through the
Service Portal. A Flow Designer flow stores each request in a custom table,
sends a confirmation email, asks the System Administrator for approval, and
updates Assigned to and Approval Status from the decision.

## Features
- Network Request catalog item with 7 variables and an auto-filled requester variable set
- UI policy that shows the Existing ID field only for Existing connections
- Custom table u_database_table with an Approval Request related list
- Flow Designer flow: create record, send email, approval, approved/rejected update

## Tools used
Service Portal, Service Catalog, Flow Designer, ServiceNow Personal Developer Instance

## Repository contents
- network-request-management-servicenow/Final_Project_Report.docs/ : project documents for each phase, including the final report
- network-request-management-servicenow/Screenshots/ : output screenshots

## How to test
1. Open dev381006.service-now.com/sp and search Network Requests.
2. Fill in the form and click Order Now.
3. Open the Database Table record and approve the request.

## Author
Pentareddy Ruhin
