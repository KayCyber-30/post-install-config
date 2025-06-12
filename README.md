# Post-Install-Configuration
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles (for grouping permissions)




- Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)




- Configure Teams
  

- Allow anyone to create tickets



- Configure Agents (workers)
  


- Configure Users (customers)


- Configure SLA


- Configure Help Topics (For when users create a ticket)




<h2>Configuration Steps</h2>

- Configure Roles (for grouping permissions)
Admin Panel -> Agents -> Roles
Supreme Admin

![image](https://github.com/user-attachments/assets/450ebc5d-0c11-4145-b6c2-5de9c7bf4b3d)

Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
Admin Panel -> Agents -> Departments
SysAdmins

![image](https://github.com/user-attachments/assets/cf801e06-e980-478b-9d2a-1c222e4bc59c)



Configure Teams
Admin Panel -> Agents -> Teams (Pull Agents from different Departments)
Online Banking

![image](https://github.com/user-attachments/assets/051c2e00-8a8a-4006-bbff-9cdbeb0e246e)


Allow anyone to create tickets
Admin Panel -> Settings -> User Settings (UNCHECK: unregistered users can create tickets)
Registration Required: Registration and login are required to create tickets 

![image](https://github.com/user-attachments/assets/5f3441ab-819d-4845-8ccb-af28de47ff9f)


Configure Agents (workers)
Admin Panel -> Agents -> Add New
 (Dept: SysAdmins)
 (Dept: Support)

 ![image](https://github.com/user-attachments/assets/c8d1b251-76c6-4734-aa77-450c245a5bd4)

 
Configure Users (customers)
Agent Panel -> Users -> Add New

![image](https://github.com/user-attachments/assets/ea9c8cc7-bd92-44b2-8f31-331bc65f409f)


Configure SLA
Admin Panel -> Manage -> SLA
Sev-A (Grace Period: 1 hour, Schedule: 24/7)
Sev-B (Grace Period: 4 hours, Schedule: 24/7)
Sev-C (Grace Period: 8 hours, Business Hours)


Configure Help Topics (For when users create a ticket)
Admin Panel -> Manage -> Help Topics
Business Critical Outage
Personal Computer Issues
Equipment Request
Password Reset
Other


