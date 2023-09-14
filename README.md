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

<h2>Configuration Steps</h2>


![image](https://github.com/droderickb/post-install-config/assets/138819497/695569f4-c7ba-4c12-a2b9-f88adba92096)

![image](https://github.com/droderickb/post-install-config/assets/138819497/b9f67a2a-dcfb-4d3e-922f-7d188ca59674)

![image](https://github.com/droderickb/post-install-config/assets/138819497/617dd098-d6ab-4a3b-9208-6b6fdab05c51)



</p>
<p>
first I created the first role of Supreme Adminastrator. This role will have the permissions to do pretty much anything

</p>
<br />

![image](https://github.com/droderickb/post-install-config/assets/138819497/7abc0f35-6210-4161-95ec-f48a2e10ba0f)


</p>
<p>
I created a department next to handle certain tickets for example, if there is a specific SLA that needs to some attention. 
</p>
<br />

![image](https://github.com/droderickb/post-install-config/assets/138819497/b827f344-40d2-42e1-8448-6210fdd749f9)

</p>
<p>
Next I created a two teams.Level I and Level II. Teams allow you to pull Agents from different Departments and organize them to handle a specific issue or user via a Help Topic or Ticket Filter. 
</p>
<br 

  
![image](https://github.com/droderickb/post-install-config/assets/138819497/3f805d26-b7e8-47d6-9adc-29faa981e70e)



Agents are given access to the help desk with the intent to respond and resolve the tickets. When adding an Agent to the help desk, they will need to be assigned to a Primary Department and given a Primary Role for the Tickets/Tasks routed to that department. Agents can be given Extended Access to additional departments of the help desk as well as assigned different Roles to those departments; this can be configured in the Access tab of the Agent’s Profile.



![image](https://github.com/droderickb/post-install-config/assets/138819497/9da68623-ad0e-4724-8c24-0c190635ed61)


![image](https://github.com/droderickb/post-install-config/assets/138819497/b39602d7-c1ab-4b19-875f-823abf008d8f)


Users can now create an account and log-in to create a ticket or check a ticket’s status. As always with osTicket, users or ticket creators are associated with their email address as the unique identifier of each user. The User Directory, located on the Agent Panel, allows agents to search tickets by user as well as create Organizations to associate the user to. Agents can be configured as internal Account Managers for tickets created by users of an Organization.
