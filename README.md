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
  <img src="https://github.com/user-attachments/assets/91f35ba9-1afd-484f-8df0-142c9d85ae29" height="75%" width="100%" alt="Definitions"/>
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
  <img src="https://github.com/user-attachments/assets/e29262ad-c174-46a5-b13c-57034685735f" height="75%" width="100%" alt="System Administrators"/>
  <img src="https://github.com/user-attachments/assets/5b9d25f5-d532-425a-8ac4-dd6a30fad4f7" height="75%" width="100%" alt="System Administrators"/>
</p>
<br />
<br />
<h3 align="center">Configure Teams</h3>
<br />
<p>
  Admin Panel -> Agents -> Teams.
</p>
<p>
  Online Banking:
</p>
<p>
  <img src="https://github.com/user-attachments/assets/94740ebf-7117-468d-9e73-00cf6ea64461" height="75%" width="100%" alt="Level II Support"/>
  <img src="https://github.com/user-attachments/assets/1a4ea8b7-3e51-4890-8cb5-350a713eda55" height="75%" width="100%" alt="Level II Support"/>
  
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
  <img src="https://github.com/user-attachments/assets/fcb24e22-166f-4763-b701-00e6eee88dc6" height="75%" width="100%" alt="ticket creations"/>
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
  <img src="https://github.com/user-attachments/assets/fbc52b82-37d0-4c26-9f13-dcdb2eccf97f" height="75%" width="100%" alt="agent one access"/>
  <img src="https://github.com/user-attachments/assets/52f54973-c51b-4448-88fe-9ec46f286022" height="75%" width="100%" alt="agent one access"/>
  <img src="https://github.com/user-attachments/assets/0fc6e232-f595-4e62-85b2-f702950ab82a" height="75%" width="100%" alt="agent one access"/>
  <img src="https://github.com/user-attachments/assets/002ba14d-ea53-4e23-9b35-8beb8c1bb935" height="75%" width="100%" alt="agent one access"/>
  <img src="https://github.com/user-attachments/assets/d52c7df7-5d19-45e7-89e1-725263556963" height="75%" width="100%" alt="agent one access"/>
<p>
<p>
  John Doe:
</p>
<p>
  <img src="https://github.com/user-attachments/assets/c1680ad9-8c9d-419e-9cd1-691b9a6103cd" height="75%" width="100%" alt="agent two"/>
  <img src="https://github.com/user-attachments/assets/42a63f1c-57ee-41e7-a856-59d1a67a941f" height="75%" width="100%" alt="agent two access"/>
</p>
<h3 align="center">Configure Users (customers)</h3>
<br />
<p>
  Admin Panel -> Users -> Add New.
</p>
<p>
  Karen User:
</p>
  <img src="https://github.com/user-attachments/assets/bb48a83a-0e90-476d-b64b-155db3ca8c26" height="75%" width="100%" alt="user access"/>
  <img src="https://github.com/user-attachments/assets/bb6166f2-f791-4c52-8c5b-7bec64bf5658" height="75%" width="100%" alt="user access"/>
  <img src="https://github.com/user-attachments/assets/f8c9e664-b8c2-4df8-ad47-d068e9c68565" height="75%" width="100%" alt="user access"/>
<p>
  Repeat the same above for Ken User.
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
  <img src="https://github.com/user-attachments/assets/5e3a6d6c-1db8-40c3-ada8-04a9761ee25e" height="75%" width="100%" alt="sev one"/>
  <img src="https://github.com/user-attachments/assets/77456fa2-1cf2-4a58-9357-4841fd6b9490" height="75%" width="100%" alt="sev one"/>
  <img src="https://github.com/user-attachments/assets/516c8ddf-ae57-4d98-a6f2-2b7ffd6d99a8" height="75%" width="100%" alt="sev two"/>
  <img src="https://github.com/user-attachments/assets/2a2695a0-eb99-4711-8abd-f6e49bbdcd9b" height="75%" width="100%" alt="sev third"/>
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
  <img src="https://github.com/user-attachments/assets/cbc27c80-e64a-4b87-a25e-08e2bf02efcb" height="75%" width="100%" alt="business critical outage"/>
  <img src="https://github.com/user-attachments/assets/f6ad5f9e-7d54-4258-8359-0af6a69454a2" height="75%" width="100%" alt="personal computer issues"/>
  <img src="https://github.com/user-attachments/assets/103db4d0-e5af-4ed2-804c-7b874dc81c06" height="75%" width="100%" alt="equipment request"/>
  <img src="https://github.com/user-attachments/assets/9864f2a2-41fa-40a7-98c3-2d55aae30161" height="75%" width="100%" alt="password reset"/>
  <img src="https://github.com/user-attachments/assets/9e75e024-6027-4304-a899-9bb240a12921" height="75%" width="100%" alt="business critical outage"/>
</p>
<br />
<br />
<p>
  This now fully configures our osTicket. I hope this guide was able to help clarify and assist you in setting up your osTicket. It is recommended to practice triaging and solving tickets.
</p>
<p>
  This is a very important skill to have for any help desk specialist, as they are the first line of communication between a company and it's customers when it comes to handling issues regarding a product or service they provide.
</p>
