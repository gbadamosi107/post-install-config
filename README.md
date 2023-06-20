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

- Step 1: Configure Roles
- Step 2: Configure Departments
- Step 3: Configure Teams
- Step 4: Allow anyone To Create Tickets
- Step 5: Configure Agents
- Step 6: Configure Users
- Step 7: Configure SLAs and Help Topics

<h2>Configuration Steps</h2><br>

<h3>Step 1: Configure Roles</h3><br>

<p>
<img src="https://i.imgur.com/Tm3p5Xy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
First, we will create a "Supreme Admin" role and give this role full access. To do this, access the Admin panel and go to "Agents," then go to "Roles," then "Add New Role." Enter the name "Supreme Admin." Navigate to "Permissions" and check each box, this gives the agents access to perform these tasks.
</p>
<br />


<h3>Step 2: Configure Departments</h3><br>
<p>
<img src="https://i.imgur.com/DcUVWiD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, we will create a "Systems Admin" department within the Admin panel. Navigate to "Agents," then go to "Departments," and select "Add New Department." Name this department "Systems Administrators." For this project, we will keep the default settings and click "Create Department."
  
</p>
<br />


<h3>Step 3: Configure Teams</h3><br>
<p>
<img src="https://i.imgur.com/WJDQ407.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, we will create a team that will allow multiple agents from different departments to collaborate on the same team. We will create the team from the Admin Panel, then navigate to "Agents," click "Teams," and select "Add New Team." Name this team "Level II Support," then click the "Members" tab and add yourself to the team.
</p>
<br />

<h3>Step 4: Allow Anyone To Create Tickets</h3><br>
<p>
<img src="https://i.imgur.com/GpJY6iU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This allows any user to create Tickets even if he/she is not in the system. To do this, from the Admin Panel, navigate to "Settings," and uncheck the box for "Require registration and login to create tickets."
</p>
<br />

<h3>Step 5: Configure Agents</h3><br>
<p>
<img src="https://i.imgur.com/ySR91KJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, we will create agents. These are help desk professionals, who will check and resolve tickets. In the Admin Panel, under "Agents," click "Add New Agent." The first agent we create is called "Jane Neal." Her email address is, "jane.neal@osticket.com" and her username is  "jane.neal." Click "Set Password" and uncheck the box for "Send the agent a password reset email." Create a password for Jane. Uncheck the box for, "Require password change at next login," and click "Set." Next, we will set Jane's permissions. Navigate to the "Access" tab, put Jane in the System Administrators" department as a "Supreme Admin." Navigate to "Teams" and add her to "Level II Support;" click "Create." Jane's account is now created. To create a second agent, named "John Nash," follow Step 5 again. Set his department as "Support," and "View Only." Once these steps are completed, you should see Jane and John under "Agents," along with their respective departments listed.
</p>
<br />

<h3>Step 6: Configure Users</h3><br>
<p>
<img src="https://i.imgur.com/hipIVGh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, we will configure users. This is anyone, such as the customers or staff, who submits tickets to the Help Desk for resolution. To add users, switch to the "Agent Panel." Under "Users," click "Create New User." Name the first user "Karen Karen," her email address is Karen@osticket.com. Click "Add User." Repeat the same steps to add another user, named "Ken Ken."
</p>
<br />

<h3>Step 7: Configure SLAs</h3><br>
<p>
<img src="https://i.imgur.com/8WYWeTX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, we will configure Service Level Agreements (SLAs). The purpose of an SLA is to prioritize ticket requests and provide the length of time in which the help desk administrator expects the tickets to be resolved. To configure the SLAs, go to the "Admin Panel," navigate to "Manage," and then to "SLA." We will create 3 separate SLA plans, "SEV A, SEV B, and SEV C." For the first SLA, click "Add New SLA Plan," name it "SEV A," assign it a grace period of "1" (representing 1 hour), and assign the schedule as "24/7." Next, create the SLA for SEV B, with a grace period of "4" (hours) and a schedule of "24/7." Last, create the SLA for SEV C with a grace period of "8" (hours) and a schedule of "Monoday-Friday."
</p>
<br />

<h3>Step 8: Configure Help Topics</h3><br>
<p>
<img src="https://i.imgur.com/csblTR6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Last, we will configure Help Topics. Help topics enable end-users to easily select from a list which issues they need resolved. In the Admin Panel, navigate to "Manage," then to "Help Topics," then click "Add New Help Topic." We will create the following 4 Help Topics, "Business Critical Outage, Personal Computer Issues, Equipment Request, and Password Reset."
</p>
<br />
