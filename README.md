<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Role-Based Access Control: Implement role-based access control by assigning appropriate roles to users, such as granting the "Supreme Admin" role to a designated administrator who will have elevated privileges within the system.
  
- Department Management: Set up and manage departments effectively, including the "System Administrators" department, ensuring that the right agents are assigned to each department for efficient ticket handling and delegation.
  
- Team Structure: Create and organize teams, such as "Level I Support" and "Level II Support," to distribute workload and streamline collaboration among agents. This ensures that tickets are routed to the appropriate teams for prompt resolution.
  
- User Ticket Creation: Enable the option to allow anyone to create tickets while requiring registration and login. This objective ensures that users, such as customers, can easily submit their support requests while maintaining a trackable and authenticated ticketing system.


- Service Level Agreements (SLA): Establish and configure SLA levels, such as "Sev-A" (1 hour, 24/7), "Sev-B" (4 hours, 24/7), and "Sev-C" (8 hours, business hours). This objective ensures that tickets are categorized based on severity and are handled within the defined response and resolution times.

<h2>Configuration Steps</h2>


<p>
Section 1: Configure Roles and Departments

Configure Roles:

Access Admin Panel -> Agents -> Roles.
Create a role named "Supreme Admin."
Configure Departments:

Access Admin Panel -> Agents -> Departments.
Create a department named "System Administrators.".</p>
<br />
<p>
<img src="https://imgur.com/xbXio15.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Section 2: Configure Teams and User Settings

Configure Teams:

Access Admin Panel -> Agents -> Teams.
Create two teams: "Level I Support" and "Level II Support."
Allow anyone to create tickets:

Access Admin Panel -> Settings -> User Settings.
Enable the option "Registration Required: Require registration and login to create tickets."</p>
<br />
<p>
<img src="https://imgur.com/fMgu76z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Section 3: Configure Agents, Users, SLA, and Help Topics

Configure Agents (workers):

Access Admin Panel -> Agents -> Add New.
Add agents named "Jane" and "John."
Configure Users (customers):

Access Agent Panel -> Users -> Add New.
Add users named "Karen" and "Ken."
Configure SLA:

Access Admin Panel -> Manage -> SLA.
Create three SLA levels: "Sev-A" (1 hour, 24/7), "Sev-B" (4 hours, 24/7), and "Sev-C" (8 hours, business hours).
Configure Help Topics:

Access Admin Panel -> Manage -> Help Topics.
Create help topics for various issues, such as "Business Critical Outage," "Personal Computer Issues," "Equipment Request," and "Password Reset."</p>
<br />
<p>
<img src="https://imgur.com/5Sb4eGF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
