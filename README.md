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

- Windows 11</b>

<h2>Post-Install Configuration Objectives</h2>

- Configuring Roles in osTicket
- Configuring Departments
- Configuring Teams
- Set who can create tickets
- Configure Agents
- Configure Users/Customers
- Configure CLA
- Configure Topics

<h2>Configuration Steps</h2>

<p>
Started the project with Setting up the available roles in osTicket from signing into the Admin portion of the site and navigating to Agents > Roles, This specific example is just added a role with my own name to have full access.
<p align="center"><img src="https://github.com/JakeMandeville/course-pictures/blob/main/OSTicket/Add%20role.png"></p>
Moved on to setting up different departments from the Agents > Departments tab, here I added a support / system admins role and a maintenance role.
<p align="center"><img src="https://github.com/JakeMandeville/course-pictures/blob/main/OSTicket/Create%20department.png"></p>
From here navigating to the Agents > Teams tabs would allow more teams to be added to the ticketing system so you can further organize who is responsible for which tickets, here is an example for adding a team for an online banking team.
<p align="center"><img src="https://github.com/JakeMandeville/course-pictures/blob/main/OSTicket/Create%20teams.png"></p>
Going to the Settngs > Users tab will allow you to edit the settings for users of your ticketing platform, here I set it to allow anyone to create a ticket even without registering an account.
<p align="center"><img src="https://github.com/JakeMandeville/course-pictures/blob/main/OSTicket/users%20settings.png"></p>
Back in the Agents tab you can add new agents to work on tickets.
<p align="center"><img src="https://github.com/JakeMandeville/course-pictures/blob/main/OSTicket/Creating%20agents.png"></p>
Even though we allowed anyone to create tickets without having to register we can still set users in the system, for this you will need to go from the Admin Panel into the Agent Panel, using the Users tab you can add more users.
<p align="center"><img src="https://github.com/JakeMandeville/course-pictures/blob/main/OSTicket/Add%20users.png"></p>
Set the SLA (Service Level Agreement) to help set how priorities of tickets should be managed depending on how severe the issue is, this is done back in the Admin panel, go to the Manage > SLA tabs.
<p align="center"><img src="https://github.com/JakeMandeville/course-pictures/blob/main/OSTicket/Add%20SLA.png"></p>
Finally, you can set up different Topics or request types from the Manage > Help Topics tab, this will help categorize issues into specific types of problems.
<p align="center"><img src="https://github.com/JakeMandeville/course-pictures/blob/main/OSTicket/Add%20topics.png"></p>
This can be use as a starting base that can be edited over time as needed. Going back to any of these tabs will allow you to edit any of these categories to further configure your ticket system.
</p>
