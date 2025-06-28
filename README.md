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
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
