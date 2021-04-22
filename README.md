# CaseManagement
Probably this is the term and idea which is as old as the IT industry. So many solutions are out there which are mostly overkill for most enterprises. In most cases, it seems like killing a small bird using tanks/canons. The overhead can be any of these (not limited to) - 

<ol><li>Cost</li><li>Complexity</li><li>Technology Specific Developers are required </li><li>Hard to find above </li><li>Dependency on a specific platform </li><li>And many more...</li></ol>

Lets bridge that need of simple case management solution's need by creating a simple yet powerful solution. A solution which should be so easy and straight-forward using which - A Business Analyst should be able to create a robust workflow system for any business need(s) such as: 

<h6>
<ol>
<li>FOIL - Freedom of Information Law</li>
<li>Procurement</li>
<li>Material Requisition</li>
<li>Document Approval</li>
<li>Leave Approval</li>
<li>Medi Claim</li>
 <ol>
And so on......(literally anything you can think of)...
</h6>

# CaseManager
A case management  solution using latest Spring-Boot and Spring-Security. For case-documents / content-storage any of these can be used as repository : 
<ul><li>FileNet</li><li>Alfresco</li><li>MongoDB</li><li>Documentum</li><li>SAN</li><li>NAS</li><li>Database - Oracle/Postgres/MSSQL/MySQL etc.</li></ul>

Source code coming soon...

# Login Screen

![casemanager](https://github.com/ajkr195/CaseManager/blob/master/scereenshots/1.png)


# Dashboard

Create all your Clusters/Agencies/ProgramAreas (Departments), Workflows with Steps, Case Document Types dynamically. All of them can be seen here on the Dashboard. Every view is security driven. Different roles will see different available features.


![casemanager](https://github.com/ajkr195/CaseManager/blob/master/scereenshots/3.png)

# Add User

Users can be managed in the Database or Can be accessed and authenticated/authorized from LDAP/AD. 

![casemanager](https://github.com/ajkr195/CaseManager/blob/master/scereenshots/8.png)


# View Different Case Lists

See different views of your case list. And filter them per your need and convenience.

![casemanager](https://github.com/ajkr195/CaseManager/blob/master/scereenshots/16.png)


# Filter Cases by their Status


![casemanager](https://github.com/ajkr195/CaseManager/blob/master/scereenshots/17.png)


# Filter Cases by your Program Areas


![casemanager](https://github.com/ajkr195/CaseManager/blob/master/scereenshots/18.png)


# Case List

Manage Cases as Admin/ProgramArea Head or as a case worker. All roles will have their own privileges. 

![casemanager](https://github.com/ajkr195/CaseManager/blob/master/scereenshots/4.png)


# Add Documents to your case

Add and Manage case documents. Choose and define your own repository where doucments can be stored. Storage can be either of these - Some Content Management System repository like - FileNet/Alfresco/MongoDB/Documentum/SAN/NAS or simply a Database.


![casemanager](https://github.com/ajkr195/CaseManager/blob/master/scereenshots/15.png)



# Case Lock

When a user starts working, the case gets locked to his/her name. Which can be unlocked by him/herself and also by Program Area Manager. Till a case stays in Locked condition, the users will be able to add documents to it but will be able to access it only in READ-ONLY mode.

![casemanager](https://github.com/ajkr195/CaseManager/blob/master/scereenshots/6.png)


# Case Unlock

![casemanager](https://github.com/ajkr195/CaseManager/blob/master/scereenshots/7.png)


# Access Denied

When a user starts tries to access anything which he/she is not entitled to, access denied message is issued like below:

![casemanager](https://github.com/ajkr195/CaseManager/blob/master/scereenshots/11.png)

# As Admin user, Manage/Monitor the entire infrastructure

![casemanager](https://github.com/ajkr195/CaseManager/blob/master/scereenshots/20.png)


# Create your own workflow/steps etc like below:

![casemanager](https://github.com/ajkr195/CaseManager/blob/master/scereenshots/12.png)

# Track the status/steps of your workflow 

Track the status of your workflow from START/LAUNCH to CLOSE

![casemanager](https://github.com/ajkr195/CaseManager/blob/master/scereenshots/5.png)


# Configure/send email (DL) at every step


![casemanager](https://github.com/ajkr195/CaseManager/blob/master/scereenshots/22.png)


# Define your SLA for your Case Types

And get alerts accordingly. x Days before deadline. x number of reminders on day before deadline.


![casemanager](https://github.com/ajkr195/CaseManager/blob/master/scereenshots/21.png)


# Search Your Cases 

Track the status of your workflow from START/LAUNCH to CLOSE

![casemanager](https://github.com/ajkr195/CaseManager/blob/master/scereenshots/19.png)



# Get full history of your case at any time

History of your case

![casemanager](https://github.com/ajkr195/CaseManager/blob/master/scereenshots/13.png)

# Update To/From External Systems. 

At every step GET/POST requests to external systems.

