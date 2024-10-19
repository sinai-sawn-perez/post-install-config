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

- Configure Roles (for grouping permissions)
- Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
- Configure Teams
- Allow anyone to create tickets
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics (For when users create a ticket)

<h2>Configuration Steps</h2>

<p>
<img src="https://github.com/user-attachments/assets/42537132-e1e2-48bc-83ba-8cc7bbfeba2c"/>
</p>
<p>
To configure Roles for your Organization first sign into the osTicket Agent Page as an admin. Begin by selecting the admin panel then, under the Agent tab select Roles. You can add/delete roles within your company, as well as define those roles and their permissions from this menu. See the image above for an example of the Agent Ticket Permissions menu.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/6ded1770-27c9-4d04-95ce-02559b08d231"/>
</p>
<p>
You can also configure Deparments while within the Agents tab. Select Departments to view/create Dapartments, you can also edit existing Departments in this tab. When creating/editing a Department you are able to set the Department's SLA, assign a Manager, set automatic responses, or adjust the ticket assignment of the Department. See the image above for an example of the Department creation menu.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/f2891e8e-2fa1-4050-ab27-ccce2b37be42"/>
</p>
<p>
<img src="https://github.com/user-attachments/assets/d0f99387-3b68-4c1c-9fd3-50aff5bbfa9b"/>
<p>
New teams and Agents can also be created within the Agents tab. During creation you have the ability to assign Agents to specific Departments. Agents can also be brought in across multiple Departments and assigned to a Team to work on a ticket requiring the skills or resources of multiple Departments.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/efcaa16e-d93a-4957-9a3f-57c50843dbb3"/>
</p>

<p>
By default Agents have permission to create new Users, alternatively users can create their own accounts or submit tickets under a guest account. If a User account is attatched to a ticket they will be able to check the status of the ticket as it's updated - and if autoresponses are enabled Users will recieve updates to the email address associated with the account.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/331be42a-6dda-4f14-a7af-6390003728c6"/>
</p>
<p>
From the Manage tab you can creat or edit SLA's (Service Level Agreement) for your organization. By adding new SLA's you create additional options for Agents to choose from when marking a new ticket's severity. 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/d93b2f09-d176-4e03-b14e-5488766c5902"/>
</p>
<p>
<img src="https://github.com/user-attachments/assets/0c894249-5453-4029-ad9d-9154ed67511d2"/>
</p>
<p>
Help Topics can be created and edited within the Manage tab as well. In the first image above, see an example of an admin account creating a help topic for a specific type of issue - critical business outages. Then in the second image, see the an example of the admin attaching a high priority SLA to the topic to mark tickets related to "critical business outages" with the appropriate SLA for the severity of the issue. This is just one example, osTicket is entirley customizable to suit the specific needs of the organization.
</p>
