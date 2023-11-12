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

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Users, Agents
- Configure SLA

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/nF4JGGx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

This shows the "Roles" category that was created under Admin Panel>Agents>Roles. "Supreme Admin" was created for a role. "Permisssions" were chosen for this role.
<p>
<img src="https://i.imgur.com/AZzm2zO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

I created "Departments" were tickets are routed to from a triage stand point. "System Administrators" is the created department. Admin Panel>Agents>Departments 
<p>
<img src="https://i.imgur.com/17NOyvs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

"Level II Support" was created for a team. Admin Panel>Agents>Teams. Team members then would be added to the team.
</p>
<img src="https://i.imgur.com/Lbd5rr6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

For Agents, Dave, Jane, John were created and placed on different teams. Admin Panel>Agents>Add New. For these agents, access, permissions were added to each agent depending on role.

<p>
<img src="https://i.imgur.com/S74cgZP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Here I created users Karen and Ken who are customers. Agent Panel>Users>Add New. Organization and their emails will be added to each user.
<p>

<img src="https://i.imgur.com/Hi7Mpic.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

Three different levels of SLAs were created. SEV-A, SEV-B, SEV-C. Admin Panel>Manage>SLA. In each SLA, a grace period and schedule were added. These help with rersponse times and during which hours to be completed by.
<p>

<img src="https://i.imgur.com/eecgg0U.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

"Help Topics" category is created which helps Users and Agents with questions or to report a problem. Admin Panel>Manage>Help Topics
