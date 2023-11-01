# post-installation

We will be configuring 

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


Now that you have a better understanding understanding roles and how it works with tasks and permissions. Let's look at some examples: 


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

to create a Team, go to your Admin Panel - Agents Tab - Click on Teams. Then click Add New Team on the right

![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/07a8f1e6-21fe-47b0-89fb-70fe056ba497)

We are calling naming the team: Level II Support 

![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/5215ae3c-b550-4d7b-b7ac-fb7da0011cfa)

Then go to the members tab 
I will add myself 

![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/a118fc5f-3fbf-4da9-9797-3727f734f605)

![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/0a6dfb14-35eb-4764-871a-d3aa21293a3b)


Next, we are going to configure to allow anyone to create tickets

Go to Admin Panel -> Settings -> Users Settings


Make sure that Registration Required is unchecked 

![image](https://github.com/christyguajardo/osTicket-post-installation-setup/assets/147533626/d236e0ae-5750-4bb7-a916-1f824d4889c3)


We are going to creat some Agents

but let's define Agents: Agents are given access to the help desk with the intent to respond and resolve the tickets. When adding an Agent to the help desk, they will need to be assigned to a Primary Department and given a Primary Role for the Tickets/Tasks routed to that department. Agents can be given Extended Access to additional departments of the help desk as well as assigned different Roles to those departments; this can be configured in the Access tab of the Agent’s Profile.


