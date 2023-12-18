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
- Configure Help Topics

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
  Agents are given access to Help Desk with the intent to respond to and reslove tickets. These are your workers. This can be done from Admin Panel > Agents > Agents > Add New Agent. 
</p>
<br />

<h3>Configuring Users(customers)</h3>

![image](https://github.com/GavinInSpace/post-install-config/assets/153689700/44fafda0-cda8-4d02-b220-aef6760a95b9)

<p>
  Unlike the steps so far, to configure Users we will have to use the Agent Panel as opposed to the Admin Panel. Go to Agent Panel > Users > Add User. These will be the accounts for the customers or whoever is going to be submitting tickets to the help desk. You can Assign a default password to Users or Agents and then prompt them to change it upon first login. 
</p>
<br />

<h3>Configuring SLA</h3>

  ![image](https://github.com/GavinInSpace/post-install-config/assets/153689700/907b770d-2837-4ae5-b322-a7af0f7b5a41)

<p>
  SLA is the Service Level Agreement. The purpose of an SLA is to provide a timeline on which the Help Desk Admin wishes tickets to be resolved. There are usually different tiers of the SLA (Sev-A, Sev-B, Sev-C) that describe different timelines of completion based on severity. To create an SLA go to Admin Panel > Manage > SLA. 
</p>
<br />

<h3>Configure Help Topics</h3>

![image](https://github.com/GavinInSpace/post-install-config/assets/153689700/0b257097-fe54-4fe8-a9e3-6bbd2a4e7463)

<p>
  Finally, you can also create different help topics that help describe the nature of the problem and allow easy identification of what type of problem it is and maybe even the severity. This can be found in Admin Panel > Manage > Help Topics. Remember any information about these topics and more can be found in the osTicket documentation and should be referenced as much as needed. Thank you for reading and I hope this was helpful!
</p>
