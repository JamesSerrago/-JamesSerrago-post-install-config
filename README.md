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
- Allow Anyone to Create Tickets
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  Login to osTicket with the login we created in the previous section.
  
  -Navigate to the Admin panel
  ->Then the Agents tab
  ->Then the Roles tab



  Create a new role and call it Supreme Admin.

  Allow it all permissions and create the role.
  
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In order to configure departments we still need to be in the Admin panel then Agents tab-> Departments tab

Create new department and we can name it System Administrators


</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In order to configure teams we will need to head to the Admin Panel -> Agents -> Teams

We can then name it something like Level II Support
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To make sure anyoneone can create tickets we will need to head to Admin Panel -> Settings -> User Settings 

Make sure that Require Registration is unchecked to allow anonymous ticket creation.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In order to configure and add agents we will need to go through Admin Panel -> Agents -> Add New

We can use whatever names we want for example Jane Dough. We can then set there username, password and job status such as their department and permissions
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In order to configure some new users we will need to head through the Agents Panel -> Users -> Add New
and we can use whatever names we want here as well.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In order to configure SLA's we will need to go to the Admin Panel -> Manage -> SLA

From here we can create a new SLA plan and call it SEV-A for example. This will allow us to set up a rule that we can follow in order to prioritize tcikets that we may receive.

We can set up a grace period that gives us a idea of how long you will have to fulfill the ticket. Then also setup a schedule to to see if a timeframe of availability will matter for the ticket.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In order to configure and add agents we will need to go through Admin Panel -> Agents -> Add New

We can use whatever names we want for example Jane Dough. We can then set there username, password and job status such as their department and permissions
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In order to configure and add agents we will need to go through Admin Panel -> Agents -> Add New

We can use whatever names we want for example Jane Dough. We can then set there username, password and job status such as their department and permissions
</p>
<br />
