<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Installation Configuration</h1>
A walkthrough which details the proccess of setting up a mock help desk ticketing system using osTicket.

_This tutorial assumes you have already completed the steps found in the previous repository:_

[Installing osTicket](https://github.com/Josh-arendt/osTicket_Prereqs_Installation)


<p align="center"><br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Broad Concepts</h2>

- Create roles
- Create Departments
- Create Teams
- Create Agents
- Create SLAs
- Create Help Topics 

<h2>Configuration Steps</h2>

Use the following link to access the help desk log in page:

[Help Desk Login Page](http://localhost/osTicket/scp/login.php)

<p>

<h2></h2>

![image](https://github.com/Josh-arendt/osTicket_Post_Installation_Configuration/assets/140751318/acd1c3a8-32fe-4fdc-9ecf-07e2f24ec9ff)

</p>
<p>
Log in to osTicket as the previously-made admin
</p>
<br />
<h2>Create Roles</h2>
<p>

![image](https://github.com/Josh-arendt/osTicket_Post_Installation_Configuration/assets/140751318/887aec3c-4974-452b-a657-81436f6c03b9)

</p>
<p>
Start by selecting the "Admin Panel."
</p>
<br />

<p>

![image](https://github.com/Josh-arendt/osTicket_Post_Installation_Configuration/assets/140751318/aefdb634-7d08-42a7-803d-8bfc0c5e7ede)

<p>
Select the "Agents" tab, then "roles", then click "Add New Role."
</p>
<br />

<p>

![image](https://github.com/Josh-arendt/osTicket_Post_Installation_Configuration/assets/140751318/39f766fe-8138-4318-8a1f-07ccb4e3b9b9)

![image](https://github.com/Josh-arendt/osTicket_Post_Installation_Configuration/assets/140751318/56c434bc-17a1-4a18-a421-e435c12f898b)

![image](https://github.com/Josh-arendt/osTicket_Post_Installation_Configuration/assets/140751318/9b1336ff-2d27-4812-8831-7e6a6bbc1d75)

![image](https://github.com/Josh-arendt/osTicket_Post_Installation_Configuration/assets/140751318/c48e37ca-8050-474f-83c8-be6330340e0f)

<p>
Name the role. Select the desired Ticket, Tasks, and Knowledgebase permissions and select "Add Role." 
</p>
<br />

<p>

![image](https://github.com/Josh-arendt/osTicket_Post_Installation_Configuration/assets/140751318/dc84b7ed-79cf-4993-8714-0614346d8687)

</p>
<p>
New Role has been created!
</p>
<br />

<h2>Create Departments</h2>

<p>

![image](https://github.com/Josh-arendt/osTicket_Post_Installation_Configuration/assets/140751318/abe0a4eb-98c0-4966-9453-917dce06e885)

</p>
<p>
Back in the Admin Panel, go to Agents -> Departments and select "Add New Department."
</p>
<br />

<p>

![image](https://github.com/Josh-arendt/osTicket_Post_Installation_Configuration/assets/140751318/62a8a05c-d1e7-45e2-ada0-9823a71ed97d)

![image](https://github.com/Josh-arendt/osTicket_Post_Installation_Configuration/assets/140751318/4c014f07-51d9-42b7-b657-0099aacc1599)

</p>
<p>
Fill out the necessary settings and access permissions. Click 'Create Dept."
</p>
<br />

<h2>Create Agents</h2>

<p>

![image](https://github.com/Josh-arendt/osTicket_Post_Installation_Configuration/assets/140751318/a7c0766c-4dc2-4c6c-a9db-d46e1567c144)

</p>
<p>
Back in the Admin Panel, go to Agents -> Agents and select "Add New Agent."
</p>
<br />

<p>

![image](https://github.com/Josh-arendt/osTicket_Post_Installation_Configuration/assets/140751318/d9c58ab0-bc52-4a42-ab29-bba3269e72ca)

</p>
<p>
Input Agent name and user name. Click "Set Password."
</p>
<br />

<p>

![image](https://github.com/Josh-arendt/osTicket_Post_Installation_Configuration/assets/140751318/91367127-8669-41e6-8211-0fc5c098ed03)

</p>
<p>
This step depends on your own needs. Whether you want to manually set the Agents' password or have them create their own password. Click "Select."
</p>
<br />

<p>

![image](https://github.com/Josh-arendt/osTicket_Post_Installation_Configuration/assets/140751318/f12b825d-ad07-4602-bca2-c0d67d3fd8b4)

![image](https://github.com/Josh-arendt/osTicket_Post_Installation_Configuration/assets/140751318/e4463976-de82-4cab-b883-6e7bb5e88875)

</p>
<p>
Go to the Access tab and apply desired access settings. Click "Create"
</p>
<br />

<p>

![image](https://github.com/Josh-arendt/osTicket_Post_Installation_Configuration/assets/140751318/83a64ab9-9acb-43df-ae4e-4632eadbd96d)


</p>
<p>
Agent has been created. 
</p>
<br />

<h2>Create Users</h2>

<p>

![image](https://github.com/Josh-arendt/osTicket_Post_Installation_Configuration/assets/140751318/17afe3ef-2fd2-48ff-8839-4f777f680c95)

</p>
<p>
In the Agent Panel, select the "Users" tab and click "Add User." 
</p>
<br />

<p>

![image](https://github.com/Josh-arendt/osTicket_Post_Installation_Configuration/assets/140751318/85d4ac5d-7906-451e-b7e6-32e64dfc227a)

</p>
<p>
Fill out user information. Click "Add User." 
</p>
<br />

<h2>Create SLA</h2>

<p>

![image](https://github.com/Josh-arendt/osTicket_Post_Installation_Configuration/assets/140751318/3ff6fdcf-b314-451c-a120-b0c123b237fc)

</p>
<p>
In the Admin Panel, go to Manage -> SLA and click "Add New SLA Plan."
</p>
<br />

<p>

![image](https://github.com/Josh-arendt/osTicket_Post_Installation_Configuration/assets/140751318/808d7ba1-690d-473b-8e6b-d9c74108d155)

</p>
<p>
Name and adjust desired SLA settings. Click "Add Plan."
</p>
<br />

<h2>Create Help Topics</h2>

<p>

![image](https://github.com/Josh-arendt/osTicket_Post_Installation_Configuration/assets/140751318/f2bb8c06-6c22-4731-ac4f-7feee74c138e)

</p>
<p>
Back in the Admin Panel, go to Manage -> Help Topics -> and click "Add New Help Topic."
</p>
<br />

<p>

![image](https://github.com/Josh-arendt/osTicket_Post_Installation_Configuration/assets/140751318/156bd787-a899-400a-9545-e24911255663)

![image](https://github.com/Josh-arendt/osTicket_Post_Installation_Configuration/assets/140751318/93500196-31ea-4bfe-9a1f-a0879bd59057)

</p>
<p>
Name the Help Topic. Assign desired Help Topic Ticket options. Click "Add Topic. "
<br />

<p>

![image](https://github.com/Josh-arendt/osTicket_Post_Installation_Configuration/assets/140751318/5e7d2846-c92d-4131-8f7e-56e4a66c0091)

</p>
<p>
New Help Topic has been created. 
</p>
<br />

<h2>End of Tutorial</h2>






