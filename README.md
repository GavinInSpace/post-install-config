<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents
- Configure Customers
- Configure SLA

<h2>Configuration Steps</h2>

<h3>Configuring Rolls</h3>

![image](https://github.com/GavinInSpace/post-install-config/assets/153689700/dddd7bee-3ca7-4220-8d01-ad0039a08799)

<p>
  In the osTicket documentation it defines rolls as the permissions granted to Agents per Department that they have acces to. You can set rolls and create your own on from the Admin Panel. Navigate to Agents > Rolls. The "Add New Roll" button will allow you to create custom rolls with custom permissions.
</p>
<br />

<h3>Configuring Departments</h3>

![image](https://github.com/GavinInSpace/post-install-config/assets/153689700/4badc448-f78c-4c30-af69-fb69d82d0336)

<p>
  Tickets can be routed from multiple Departments through the Help Desk and different settings can be set for different departments. This can be done from the Admin Panel > Agents > Departments. New departments can be added and customized from the "Add New Department" button. This way you can create or change SLA agreements, schedules, assign managers, etc.
<br />

<h3>Configuring Teams</h3>

![image](https://github.com/GavinInSpace/post-install-config/assets/153689700/c05abce9-fb69-4c6d-a135-b0cc52fc420c)

<p>
  Teams allow you to pull Agents from different Departments to help a specific issue or user. To access your teams menu you go to Admin Panel > Agents > Teams. From here you can add new Teams and reconfigure existing ones.
</p>
<br />

<h3>Configuring Agents</h3>

![image](https://github.com/GavinInSpace/post-install-config/assets/153689700/470271b4-3068-4373-beb4-116f98e7cf41)

<p>
  Agents are given access to Help Desk with the intent to respond to and reslove tickets. These are your users. This can be done from Admin Panel > Agents > Agents > Add New Agent. 
</p>


