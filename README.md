<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Installed osTicket system
- Created new Roles with Permissions
- Configure Departments
- Configure osTicket Agents (Workers)
- Configure SLA & Help Topics

<h2>Configuration Steps</h2>

![Screenshot 2025-02-17 161930](https://github.com/user-attachments/assets/a848e6d2-9d0d-4d9f-93b1-a06d7e450bfa)

Completely installed all the Dependencies as well as osTicket from the Azure Virtual Machine which was a success! Now I will make some configurations and create some Roles, Departments, Agents and SLA's as examples.  

</p>
<br />

![Roles](https://github.com/user-attachments/assets/affdd18d-bf2c-492b-b2ba-ceab08881664)

Clicked on the Admin Panel, click Agents, click Roles and created a new Role name Miller Admin (for grouping permissions)
and enabled all permissions
</p>
<br />

![Create Departments](https://github.com/user-attachments/assets/857bffc9-ba47-4083-a238-bc82124c9137)

Clicked on Admin Panel, Agents, Departments. Created SysAdmins
</p>
<br />

![Setup New Users](https://github.com/user-attachments/assets/d817fa65-1787-4b88-b6da-572be9fa5205)

Created osTicket Agents ex. Joe Doe (Dept. Support) and Jane Doe (Dept. SysAdmins), to have access to certain departments with certain permissions
</p>
<br />

![Create SLA](https://github.com/user-attachments/assets/39f2e621-6ea0-4b6d-bd56-c083b7f3f473)
![New Help Topics](https://github.com/user-attachments/assets/17ee67da-958e-4c37-a1ce-1d509e226b87)

Created 3 SLA's (Sev-A grace period 1hrs Schedule 24/7, Sev-B grace period 4hrs Schedule 24/7, Sev-C grace period 8hrs Business Hours) 
Created 5 Help Topics, goto Admin Panal, Manage, Help Topics, Add New Help Topics, select Topic ex. Password Reset, Status Active, Parent Topic > Report a Problem, Add Topic and Save Change.

</p>
<br />
