<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" height="75%" width="100%"alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<!-- <h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com) -->

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used</h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<h3 align="center">Configure Roles</h3>
<br />
<p>
  Admin Panel -> Agents -> Roles.
</p>
<p>
  Supreme Admin:
</p>
<p>
  <img src="https://github.com/user-attachments/assets/889c4a85-e08a-4002-9de9-f3fbfa7871c4" height="75%" width="100%" alt="Definitions"/>
  <img src="https://github.com/user-attachments/assets/31b2f561-be08-4193-b27e-a44031aa67bd" height="75%" width="100%" alt="Permissions"/>
  <img src="https://github.com/user-attachments/assets/b4077bf5-b3f3-4408-9af6-669215c3f048" height="75%" width="100%" alt="More Permissions"/>
  <img src="https://github.com/user-attachments/assets/b459b965-9668-4e89-b6d5-1dd7d8700566" height="75%" width="100%" alt="Even More Permissions"/>
  <img src="https://github.com/user-attachments/assets/93255f7e-be12-4539-804c-c5dd1fa9b518" height="75%" width="100%" alt="Sys Admin Success"/>
</p> 
<p>
  After that go to permissions and check everything for: tickets,tasks and knowledge base
</p>
<p>
  Then go and click on "Add Role"
</p>
  <img src="https://github.com/user-attachments/assets/0870b767-8265-4d26-afa3-1e2e859c396b" height="75%" width="100%" alt="Sys Admin Success"/>
  <img src="https://github.com/user-attachments/assets/c8068d0e-8e14-4acb-a8ec-695727e7e909" height="75%" width="100%" alt="Sys Admin Success"/>
  <img src="https://github.com/user-attachments/assets/95a48449-a584-4ad7-b43d-1b6790ef5c26" height="75%" width="100%" alt="Sys Admin Success"/>
  <img src="https://github.com/user-attachments/assets/3db137c7-3fa3-4d29-8b18-c0bb23cf7075" height="75%" width="100%" alt="Sys Admin Success"/>
<p>
</p>
<br />
<h3 align="center">Configure Departments</h3>
<br />
<p>
  Admin Panel -> Agents -> Departments.
</p>
<p>
  System Administrators:
</p>
<p>
  <img src="https://i.imgur.com/83gWQsO.png" height="75%" width="100%" alt="System Administrators"/>
  <img src="https://i.imgur.com/oGLXmQv.png" height="75%" width="100%" alt="System Administrators"/>
</p>
<br />
<br />
<h3 align="center">Configure Teams</h3>
<br />
<p>
  Admin Panel -> Agents -> Teams.
</p>
<p>
  Level II Support:
</p>
<p>
  <img src="https://i.imgur.com/BnPrcDH.png" height="75%" width="100%" alt="Level II Support"/>
</p>
<br />
<br />
<h3 align="center">Allow anyone to create ticket</h3>
<br />
<p>
  Admin Panel -> Settings -> User Settings.
</p>
<p>
  Make sure "Require registration and login to create tickets" is not selected:
</p>
<p>
  <img src="https://i.imgur.com/QsJjOuM.png" height="75%" width="100%" alt="ticket creations"/>
</p>
<br />
<br />
<h3 align="center">Configure Agents (workers)</h3>
<br />
<p>
  Admin Panel -> Agents -> Add New.
</p>
<p>
  Jane Doe:
</p>
  <img src="https://i.imgur.com/ujpOdKM.png" height="75%" width="100%" alt="agent one access"/>
<p>
  John Doe:
</p>
<p>
  <img src="https://i.imgur.com/NcCP0v9.png" height="75%" width="100%" alt="agent two"/>
  <img src="https://i.imgur.com/aKTJ01A.png" height="75%" width="100%" alt="agent two access"/>
</p>
<h3 align="center">Configure Users (customers)</h3>
<br />
<p>
  Admin Panel -> Users -> Add New.
</p>
<p>
  Ken User:
</p>
  <img src="https://i.imgur.com/vbPd3uK.png" height="75%" width="100%" alt="user access"/>
<p>
  Repeat the same above for Karen User.
</p>
<br />
<br />
<h3 align="center">Configure SLA</h3>
<br />
<p>
  Admin Panel -> Manage -> SLA.
</p>
<p>
  Sev-A (1 hour, 24/7).
</p>
<p>
  Sev-B (4 hours, 24/7).
</p>
<p>
  Sev-C (8 hours, business hours):
</p>
<p>
  <img src="https://i.imgur.com/6AAF3Ju.png" height="75%" width="100%" alt="sev one"/>
  <img src="https://i.imgur.com/izcD74X.png" height="75%" width="100%" alt="sev two"/>
  <img src="https://i.imgur.com/xKzdp7w.png" height="75%" width="100%" alt="sev three"/>
</p>
<br />
<br />
<h3 align="center">Configure Help Topics</h3>
<br />
<p>
  Admin Panel -> Manage -> Help Topics.
</p>
<p>
  Business Critical Outage.
</p>
<p>
  Personal Computer Issues.
</p>
<p>
  Equipment Request.
</p>
<p>
  Password Reset.
</p>
<p>
  <img src="https://i.imgur.com/Xdhp63v.png" height="75%" width="100%" alt="business critical outage"/>
  <img src="https://i.imgur.com/3Y7k2o1.png" height="75%" width="100%" alt="personal computer issues"/>
  <img src="https://i.imgur.com/Z0eIGea.png" height="75%" width="100%" alt="equipment request"/>
  <img src="https://i.imgur.com/ndOdtTZ.png" height="75%" width="100%" alt="password reset"/>
</p>
<br />
<br />
<p>
  This now fully configures our osTicket. I hope this guide was able to help clarify and assist you in setting up your osTicket. It is recommended to practice triaging and solving tickets.
</p>
<p>
  This is a very important skill to have for any help desk specialist, as they are the first line of communication between a company and it's customers when it comes to handling issues regarding a product or service they provide.
</p>
