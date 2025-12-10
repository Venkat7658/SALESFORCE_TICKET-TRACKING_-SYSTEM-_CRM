✅ TCS SALESFORCE LAST MILE PROJECT DOCUMENTATION
SERVICE REQUEST & TICKET TRACKING SYSTEM (CRM)
By Smart CRM Solutions
________________________________________
-----------------------------------------
PROJECT OVERVIEW
Smart CRM Solutions provides Salesforce platform support to thousands of internal users. Employees frequently raise Salesforce-related issues, enhancements, or access requests. Previously, these requests arrived through emails, phone calls, or were tracked manually in Excel sheets, causing delays, miscommunication, and lack of visibility into ticket progress.
To solve this, we built a custom Salesforce-based Ticket Tracking CRM that allows the System Administrator to log, track, update, and manage every Salesforce-related request in a centralized system. This application enables better organization, improves internal communication, provides visibility into ticket status, and ensures higher efficiency in handling Salesforce tasks.
________________________________________
-----------------------------------------
OBJECTIVES
The primary goals of the Service Request & Ticket Tracking CRM are:
•	To centralize all internal Salesforce support requests in a structured system.
•	To maintain detailed records of requester, department, priority, and ticket metadata.
•	To automate status tracking and improve transparency for internal users.
•	To eliminate dependency on Excel sheets and email-based tracking.
•	To create a scalable foundation for future automations such as notifications, escalations, and approvals.
•	To allow the System Administrator to efficiently manage workload and track time.

⭐ PHASE-WISE DOCUMENTATION________________________________________

✅ PHASE 1 — Problem Understanding & Business Need
The business problem was:
•	Your company tracks tickets in ServiceNow, but Salesforce-related issues were not tracked properly.
•	Requests arrived via email or phone, causing mismanagement and delays.
•	You manually tracked them in Excel, which was inefficient.
•	You wanted a central place to log Salesforce tickets inside Salesforce, so you could automate notifications and status updates.
Business Need Summary
A custom ticket-tracking CRM inside Salesforce is needed to:
•	Log and track Salesforce change requests.
•	Automate communication to requesters.
•	Improve visibility of ticket progress.
•	Replace manual spreadsheet tracking.
Stakeholders Identified
•	Admin (you) who manages Salesforce tasks.
•	Employees / Users submitting ticket requests.
•	Approvers (if required) for specific types of changes.
Industry Context
This falls under IT Helpdesk / Internal Salesforce Support.
________________________________________
✅ PHASE 2 — Org Setup & Configuration
From the video:
•	You were inside Salesforce Setup → Object Manager.
•	You created a new Custom Object named Salesforce Tickets.
•	You configured the object with:
o	Auto-number format
o	Searchability enabled
o	Activity tracking enabled
o	Field history tracking enabled
•	You created a custom tab for the object.
•	You created a Lightning App named “Salesforce Ticket Tracker”.
These actions correspond to:
•	Salesforce Org Configuration
•	Object Tab Setup
•	App Navigation Setup
________________________________________
✅ PHASE 3 — Data Modeling & Relationships
Custom Object Created
Object Name: Salesforce Ticket (API: Salesforce_Ticket__c)
Standard Fields Used
•	Owner
•	Created Date
•	Created By
•	Auto-number ticket field
Custom Fields You Created
Below are all fields mentioned in your transcript:
Lookup Fields
1.	Requester (User lookup)
2.	Approver (User lookup – optional)
Date Fields
3.	Requested Completion Date
4.	Completed Date
Picklists
5.	Status
o	New
o	In Development
o	In Testing
o	Closed
o	Rejected
6.	Priority
o	High
o	Medium
o	Low
7.	Department
( company has many departments; list not provided here, but video shows they were added manually)
8.	Primary Object
(Picklist of Salesforce objects you track changes for)
9.	Request Type
o	Change
o	Addition
o	New User
o	Existing User
Text / Rich Text Fields
10.	Description (Rich Text)
11.	Admin Notes (Long Text Area)
Page Layouts
•	You arranged fields in logical order.
•	You added Notes & Attachments to related list.
Compact Layout
•	You created/edited compact layout to show:
o	Type
o	Priority
o	Status
This appears in the Highlights Panel.
________________________________________
✅ PHASE 4 — Process Automation (So far none)
no flows, workflows, validation rules, or automations were created yet.
Phase 4 will note: Automation planned as future enhancement
________________________________________
✅ PHASE 5 — Apex Development (None Yet)
“No Apex automation implemented in this phase. The system is built using declarative features only.”
________________________________________
✅ PHASE 6 — UI Development
You performed:
•	Creating a Lightning App
•	Setting visibility of the custom tab
•	Editing Record Page (Highlights Panel) via Lightning App Builder
This includes:
•	Tabs
•	Record Pages
•	Lightning App
•	Compact Layout
•	Page Layout customizations
________________________________________
✅ PHASE 7 — Integration (Not Done Yet)
“No integrations implemented in this phase. Future enhancements include Email-to-Case or external request intake.”
________________________________________
✅ PHASE 8 — Data Management & Deployment
•	Manual record creation
•	No sandbox deployment done
________________________________________
✅ PHASE 9 — Reports, Dashboards & Security
“Reporting and dashboards will be added in later phases.”
“Default security applied via System Administrator profile.”
________________________________________
✅ PHASE 10 — Testing
Nothing shown in video except a manual test:
•	You created a test ticket record to confirm the fields appear correctly.
•	You refreshed layout to verify highlights panel.
We will include this as a simple test case.

