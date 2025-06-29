<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Installation Setup</h1>
This tutorial will demonstrate the post configuration setup of the osTicket system.<br />

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/WErRgz9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
we’ve successfully completed the base installation and configuration of osTicket. Now we’ll move on to some post-installation system administration, starting with creating custom user roles within the help desk.

To begin, navigate to:
Admin Panel → Agents → Roles

From here:

Click “Add New Role”

Enter a name for the role (e.g., SysAdmins)

Assign the appropriate permissions

In this example, the Supreme Admin role is granted full system permissions to simulate an all-access administrative user.

🔐 Note: Roles in osTicket define what each agent is allowed to see and do. Not all agents should have full access, so use roles to apply principle of least privilege where appropriate.

If configured correctly, you should see your newly created “Supreme Admin” role listed on the Roles page.
</p>
<br />

<p>
<img src="https://i.imgur.com/1wyK8VK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, we’ll set up a new department within osTicket to help organize agents based on their responsibilities.

Navigate to:
Admin Panel → Agents → Departments

From here:

Click “Add New Department”

Enter the department name (e.g., System Administrators)

Optionally configure additional settings such as:

SLA plans

Department manager

Auto-response and email settings

💡 Note: Each agent in osTicket is assigned to a department based on their role. In this example, we’re creating a System Administrators department where our Supreme Admins will be designated. This helps structure workflows and ensures proper routing of tickets and responsibilities.

Once saved, the new department should appear in your Departments list.

</p>
<br />

<p>
<img src="https://i.imgur.com/PbASDHu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After setting up your agents, the next step is to create Users — the individuals who submit support tickets when they encounter issues. These users represent your customers or clients, and their interactions form the core of the ticketing system.

In osTicket, each user is identified by their email address, which is used to track and associate all submitted tickets.

To create a new user:
Navigate to:
Agent Panel → Users → User Directory → Add New

From here, you can:

Enter the user’s name and email address

Optionally assign them to an organization

Begin tracking their ticket history and communications

</p>
<br />

<p>
<img src="https://i.imgur.com/bYvDVTg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now that we have set up a new team, we will create a new setting that will allow anyone to create tickets. Admin Panel->Settings->User Settings.
</p>
<br />

<p>
<img src="https://i.imgur.com/8RqAIp1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
With departments and teams in place, the next step is to create Agents — the help desk staff responsible for handling and resolving support tickets.

Navigate to:
Admin Panel → Agents → Add New Agent

Key Concepts:
Each Agent is assigned a primary department and a primary role within that department.

Agents can also be granted access to multiple departments, each with custom role assignments depending on their responsibilities in that area.

Roles define what an agent can view or modify, while departments determine what types of tickets they’ll handle.

You can also assign Agents to teams for cross-department collaboration.

Within the Agents tab, you’ll configure:

Login credentials

Department assignments

Role-based permissions

Team memberships

Once added, agents will be able to log in to the help desk portal, view assigned tickets, and respond according to their permissions.
</p>
<br />

<p>
<img src="https://i.imgur.com/PRm6FQl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After creating departments, the next step is to configure teams. Teams in osTicket allow you to group agents across different departments based on skill sets or support tiers. This provides flexibility in assigning tickets to specialized groups, regardless of departmental structure.

Navigate to:
Admin Panel → Agents → Teams

Key points:

A default Level I Support team is already provided.

For this example, we’ll create a Level II Support team composed of advanced technicians from multiple departments.

To create a team:

Click “Add New Team”

Enter a name (e.g., Level II Support)

Add agents who specialize in specific products or advanced issues
</p>
<br />

<p>
<img src="https://i.imgur.com/PRm6FQl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After creating departments, the next step is to configure teams. Teams in osTicket allow you to group agents across different departments based on skill sets or support tiers. This provides flexibility in assigning tickets to specialized groups, regardless of departmental structure.

Navigate to:
Admin Panel → Agents → Teams

Key points:

A default Level I Support team is already provided.

For this example, we’ll create a Level II Support team composed of advanced technicians from multiple departments.

To create a team:

Click “Add New Team”

Enter a name (e.g., Level II Support)

Add agents who specialize in specific products or advanced issues
</p>
<br />

<p>
<img src="https://i.imgur.com/PRm6FQl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After creating departments, the next step is to configure teams. Teams in osTicket allow you to group agents across different departments based on skill sets or support tiers. This provides flexibility in assigning tickets to specialized groups, regardless of departmental structure.

Navigate to:
Admin Panel → Agents → Teams

Key points:

A default Level I Support team is already provided.

For this example, we’ll create a Level II Support team composed of advanced technicians from multiple departments.

To create a team:

Click “Add New Team”

Enter a name (e.g., Level II Support)

Add agents who specialize in specific products or advanced issues
</p>
<br />

