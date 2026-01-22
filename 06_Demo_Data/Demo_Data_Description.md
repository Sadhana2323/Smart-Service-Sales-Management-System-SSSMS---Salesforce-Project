Demo Data Description

This project uses sample (demo) data to simulate a real-world Service Management System.
The demo data helps in testing objects, flows, reports, and dashboards.

1️⃣ Accounts (Customers)

Purpose:
Represents customers who raise service requests.

Demo Data Created:

Account Name	Type
ABC Electronics	Customer
TechNova Solutions	Customer
Green Energy Pvt Ltd	Customer
Smart Homes India	Customer
BlueWave Systems	Customer

Usage in Project:

Linked to Service Requests

Used in Screen Flow (Select Account)

2️⃣ Contacts

Purpose:
Represents customer contacts related to accounts.

Demo Data Created:

Contact Name	Account
Rahul Kumar	ABC Electronics
Sneha Patel	TechNova Solutions
Arjun Reddy	Green Energy Pvt Ltd
Meera Nair	Smart Homes India
Karthik S	BlueWave Systems

Usage in Project:

Linked to Service Requests

Used for email notifications

3️⃣ Service Requests

Purpose:
Represents customer service issues.

Demo Data Created:

Service Request	Status	Priority
SR-0001	New	Low
SR-0002	In Progress	Medium
SR-0003	In Progress	High
SR-0004	Completed	Medium
SR-0005	Completed	High

Usage in Project:

Triggers Record-Triggered Flow

Used in Reports & Dashboard

Used for validation rules

4️⃣ Technician Assignments

Purpose:
Tracks technician work details for each service request.

Demo Data Created:

Technician	Hours Worked	Hourly Rate
Technician A	5	₹500
Technician B	3	₹600
Technician C	4	₹450

Usage in Project:

Roll-up summary calculation

Technician hours report

Service cost calculation

5️⃣ Payments

Purpose:
Tracks payments made for completed service requests.

Demo Data Created:

Payment ID	Amount	Status
PAY-001	₹2,500	Paid
PAY-002	₹1,800	Paid
PAY-003	₹3,200	Pending

Usage in Project:

Created automatically via Record-Triggered Flow

Used in payment reports and dashboard

6️⃣ Flow Testing Data

Purpose:
Used to verify automation.

Record-Triggered Flow

When Service Request status is changed to Completed

Payment record is created automatically

Email alert is sent

Scheduled Flow

Service Requests in In Progress for more than 7 days

Priority automatically updated to High

Screen Flow

User selects Account

Enters Priority

Assigns Technician

Confirms Service Request creation

7️⃣ Reports & Dashboard Data

Reports Tested Using Demo Data:

Service Requests by Priority

Technician Hours Worked

Payment Status & Revenue

Dashboard Shows:

Open Service Requests

Monthly Revenue

Technician Workload
