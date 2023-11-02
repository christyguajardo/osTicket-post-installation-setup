# post-installation

In this demonstration, we will be configuring an osTicket.

Of course, let's start by logging into osTicket

![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/38ae3701-fb10-4b86-b112-386222c12ac8)


Once logged in, this screen should appear

![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/8993703d-4a53-41d6-99ae-0e97e43b5d69)


Also, for reference below are the various role permissions that are allowed using osTicket. As you can see, there are quite a few!

Let's define roles:

Roles are the permissions granted to Agents per Department that they have access to. Each Role has a set of permissions that can be checked/unchecked for agents given that Role in association with a Department they have access to. An unlimited number of roles can be created and assigned to Agents with access to various departments.

Role Permissions for Tickets include:

 🏗️Assign: Ability to assign tickets to agents or teams

 🏗️ Close: Ability to close tickets

 🏗️Create: Ability to open tickets on behalf of users

 🏗️Delete: Ability to delete tickets

 🏗️Edit: Ability to edit tickets

 🏗️Edit Thread: Ability to edit thread items of other agents

 🏗️Link: Ability to link tickets

 🏗️Mark as Answered: Ability to mark a ticket as Answered/Unanswered

 🏗️Merge: Ability to merge tickets

 🏗️Post Reply: Ability to post a ticket reply

 🏗️Refer: Ability to manage ticket referrals

 🏗️Release: Ability to release ticket assignment

 🏗️Transfer Ability to transfer tickets between departments


 Role Permissions for Tasks include:

 🏗️ Assign: Ability to assign tasks to agents or teams

 🏗️ Close: Ability to close tasks

 🏗️ Create: Ability to create tasks

 🏗️ Delete: Ability to delete tasks

 🏗️ Edit: Ability to edit tasks

 🏗️ Post Reply: Ability to post task update

 🏗️ Transfer: Ability to transfer tasks between departments


Hopefully, this explains roles and how it works with tasks and permissions. Let's look at some examples: 


Configure Roles

Go to: Admin Panel -> Agents -> Roles

Under Agent select Roles

![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/20785db4-9c80-403a-8f16-b0217770d1eb)

![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/a3450901-957f-46e4-9531-b16f90fa81d7)


Click on add new role: (Under Definition Tab)

![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/72f3529e-c516-40e7-aeb5-307e9a51f049)


Go to Permissions Tab

Click on all boxes  under Tickets, Tasks & Knowledgebase 
![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/62bd3960-fff7-496b-8ec0-b401496d52d2)

![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/1d008c6b-1000-46ae-81df-98439967ec91)

Click on all boxes under tasks

![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/3fe757d7-682e-4ea8-be89-2c5970cf340f)

Click box under Knoweldgebase - Click on Add Role 

![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/91bf84a6-f4ce-42d6-9c07-74ebe47a1974)

Role has been added 

![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/53c641ac-9cb6-4d6d-a0c4-3b200dace7ca)

Click on Add New Department

![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/86fb0533-6b96-4202-97b1-416fc7da30e2)

Under Name: Type in System Administrators 

![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/04e2d653-ff7a-45ae-ba2e-398da5d5b1b4)

![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/b1447c47-9f54-4d81-8e05-a380d09f0e3c)

Click on Create Dept (we are using the default settings)

![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/b5060be4-f6db-4539-86de-85088b624cdc)


Next we are configuring Teams:

Teams allow you to pull Agents from different Departments and organize them to handle a specific issue or user via a Help Topic or Ticket Filter.
Having Agents from different Departments assigned to a Team will supersede the parameters of the Agents' Department rules. For example, you can create a Help Topic associated with a partcitular product you produce and assign it to a Team of specialist Agents from different Departments. 

To create a Team, go to your Admin Panel - Agents Tab - Click on Teams. Then click Add New Team on the right

![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/07a8f1e6-21fe-47b0-89fb-70fe056ba497)

We are naming the team: Level II Support 

![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/5215ae3c-b550-4d7b-b7ac-fb7da0011cfa)

Then go to the members tab 
I will add myself 

![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/a118fc5f-3fbf-4da9-9797-3727f734f605)

![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/0a6dfb14-35eb-4764-871a-d3aa21293a3b)


Next, we are going to configure to allow anyone to create tickets

Go to Admin Panel -> Settings -> Users Settings


Make sure that Registration Required is unchecked 

![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/d236e0ae-5750-4bb7-a916-1f824d4889c3)


Next we are going to creat some Agents

Agents are given access to the help desk with the intent to respond and resolve the tickets. When adding an Agent to the help desk, they will need to be assigned to a Primary Department and given a Primary Role for the Tickets/Tasks routed to that department. Agents can be given Extended Access to additional departments of the help desk as well as assigned different Roles to those departments; this can be configured in the Access tab of the Agent’s Profile.

Click on Add New Agent

![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/24a87206-2b9f-49cb-ac55-2e2d39494a62)

Complete the fields: Name Email Address Username chten click on set password
![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/8a1abac8-3d46-4bcb-9d2a-5ef1465efacd)


Type in password and uncheck boxes: Send the agent a password reset email
                                     Require password change at next login

![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/3de2db61-06cb-4597-8c86-34a22c68bc0b)

Next, go to Access tab. We are making Jane a Supreme Admin 

Under Primary Department - select System Administrators - Then select Supreme Admin
![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/65c2cdcd-0d5f-43c0-a4bd-51281b82a736)

Next, go to Teams tab and select Level II Support

![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/7bc95691-2f6f-4614-b50d-02aeaf978e71)

Jane has now been successfully added!

![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/de387ede-4dc5-4a35-96df-48238a87484f)


Next, we are going to configure Users (customers)

Users are the ticket owners of the tickets in the help desk. When a ticket is created in the help desk, the user is associated with their email address in the User Directory of the help desk. Users can be added or deleted from the User Directory of the help desk at any time. Please note, if the user is deleted the tickets of the user must also be deleted. 

Go to - Agent Panel -> Users -> Add User 


![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/d0b7fc21-a7d4-4aa4-bfc7-c6e371bb0182)

Click Add User 

![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/99ba2167-5bbd-48bb-9053-02ef76889f1d)

Jill Hill has been added as a User

![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/bdcaa723-5bf5-40e6-856d-164e547b465f)

We will now configure an SLA

SLA Plans or Service Level Agreements, are unlimited in osTicket. The purpose of the SLA Plan is to provide a length of time in which the help desk Administrator expects tickets to be closed.
Once created, SLA Plans can be determined for Departments, Ticket Filters, and Help Topics.

Service Level Agreements: SLA Plans can be set by help topic and department to ensure the ticket is CLOSED in the allotted or specified amount of time.

Name: Plan name to be selected when assigning.

  💡Grace Period: Amount, in hours, before tickets with this SLA will become overdue if not closed in allotted time.

  💡Status: Choose Active or Disable for the plan.

  💡Transient: SLA can be overridden on ticket transfer or help topic change; if not transient, the SLA will remain the same as it is assigned on ticket creation.

  💡Ticket Overdue Alerts: This will DISABLE overdue alert notices to staff for tickets assigned this SLA.

Let's start the configuration. Go to Admin Panel -> Manage -> SLA

   Click on Add New SLA Plan 

![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/b5b651a9-16db-4f6a-b935-a4668cf04aab)

Click on Add Plan

![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/d0bf52e5-3626-4df5-a2d1-6d364f68c5ed)

Let's add another SLA!
![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/26b225a4-0dc3-4540-875c-0e678049dfe6)

This means that you have 4 hours to settle the ticket 

Last SLA we will be adding

You will have a business day (8 hours to settle the ticket)

![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/5fa42702-f6cd-4e77-9d2b-83a29329608f)

For the last part of this demonstration, Help Topics will be configured

Help Topics will help streamline your end-user’s help desk experience to ensure proper assignment and prompt response to the ticket. Create as many Help Topics as needed and can even nest Help Topics within each other for further breakdown (For example, Human Resources and Human Resources/Payroll.)

Help Topics will determine what Department the ticket is routed to which will determine which Agents have access to the ticket. The Help Topic also can determine other configurations of the ticket, such as the ticket’s SLA (or Service Level Agreement) and priority of a ticket, i.e. Emergency to Low.

There are two places where the Help Topic must be selected on New Tickets; the client portal and new tickets created internally by staff. When Users select the Help Topic, they are not aware of the configurations in place for that Help Topic.

Examples:

You are looking at the default Help Topics - Click on Add New Help Topic

![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/12a10747-ae3a-4e8c-a6c8-a5649b448f61)

Click on Add Topic - Business Critical Outage has been added

![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/1305be63-8c3b-4b24-a65a-fb848f393b90)


We will now add another Help Topic - Personal Computer Issues 

Thank you! This concludes the deomnstation for configuring an osTicket. 
