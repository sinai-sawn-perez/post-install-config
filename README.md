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
First sign into the osTicket Agent Page as an admin. Begin by selecting the admin panel, then select the Agent tab, then click on Roles. From here you can add/delete roles within your company, as well as define those roles and assign them permissions. 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/6ded1770-27c9-4d04-95ce-02559b08d231"/>
</p>
<p>
Also withing the Agents tab, select Departments to view/create dapartments for your company. From here you are able to select the Department's SLA, assign a Manager, set automatic responses, or adjust the ticket assignment of the Department.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/f2891e8e-2fa1-4050-ab27-ccce2b37be42"/>
</p>
<p>
<img src="https://github.com/user-attachments/assets/d0f99387-3b68-4c1c-9fd3-50aff5bbfa9b"/>
<p>
New teams and Agents can also be created within this tab. osTicket provides the ability to assign Agents to Departments so they only see tickets relevant to that Department. Agents can also be brought in across multiple Departments and assigned to a Team to work a specific ticket that may require the services or resources of more than one Depatment
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/efcaa16e-d93a-4957-9a3f-57c50843dbb3"/>
</p>

<p>
By default Agents have permission to create new Users, though users are able to create their own accounts or submit tickets under a guest account. If a User has an account attatched to their ticket, they will be able to check the status of the ticket as it's updated - and if you enable autoresponses then Users will recieve an email when the ticket is updated.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/331be42a-6dda-4f14-a7af-6390003728c6"/>
</p>
<p>
In the Manage tab existing SLA's (Service Level Agreements) can be updated, new SLA's can also be created here. One use of adding new SLA's is allowing Agents to have more options to choose from when marking the severity of a ticket. 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/d22b8c1b-04b0-4968-befb-cee4d8d01df1"/>
</p>
<p>
<img src="https://github.com/user-attachments/assets/d93b2f09-d176-4e03-b14e-5488766c5902"/>
</p>
<p>
<img src="https://github.com/user-attachments/assets/0c894249-5453-4029-ad9d-9154ed67511d2"/>
</p>
<p>
Specefic Help Topics can be updated or created under the Manage tab as well. In the example above, an admin account creates a topic with a high severity SLA attatched for critical business outages, though osTicket is entirley custumozable for the specific needs of the company.
</p>
