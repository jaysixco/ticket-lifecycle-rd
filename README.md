# ticket-lifecycle

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />
In this tutorial, you are going to play 3 roles:  administrator, agent, user <br>
In this tutorial, you/we are going to be creating and delegating tickets <br>

<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<strong> Part 1: Create a Ticket (User) </strong> <br>
Copy this link: http://localhost/osTicket/ <br>
Open a new tab <br>
Paste the link in the url and press Enter key <br>
Click "Open a new Ticket" <br>
  <img width="571" alt="image" src="https://github.com/jaysixco/ticket-lifecycle-rd/assets/160427311/0cff462b-2c76-42b4-ad7c-3e6603b6e462">
<br>
Fill in all the boxes with the red star next to it (email, full name, help topic, issue summary), type a summary of what the issue is, then click "Create Ticket" <br>
<img width="508" alt="image" src="https://github.com/jaysixco/ticket-lifecycle-rd/assets/160427311/4ea13a79-dcce-45fa-af9c-d4c14f36500c">
<br>

  
<strong> Part 2: Delegate the ticket (Admin) </strong><br>
Copy and paste this link - http://localhost/osTicket/scp/login.php - in a new tab <br>
Type in your admin's created username and password <br>
Username:Jay <br>
Password: Password1 <br>
(add screenshot of login page)
Click the ticket <br>
<img width="575" alt="image" src="https://github.com/jaysixco/ticket-lifecycle-rd/assets/160427311/ee1eba4c-45e1-49ce-8331-8335b139e7df"> <br>
Click Reassign, then click "Agent" <br>
<img width="581" alt="image" src="https://github.com/jaysixco/ticket-lifecycle-rd/assets/160427311/96673d6f-f066-42bd-b1f1-28d4a71cd809">
<br>
For "Assignee*:" Select an Agent, then click "Assign"<br>
<img width="388" alt="image" src="https://github.com/jaysixco/ticket-lifecycle-rd/assets/160427311/0eedf451-2a5f-460c-a874-f3beef8c5354">
<br>
Will automatically bring you to this page: <br>
<img width="575" alt="image" src="https://github.com/jaysixco/ticket-lifecycle-rd/assets/160427311/a0e6b2a8-ab02-4179-9b9c-055ff73da741">
<br>

  
<strong> Part 3: Change the priority level of the ticket </strong> <br>
Click ticket <br>
<img width="575" alt="image" src="https://github.com/jaysixco/ticket-lifecycle-rd/assets/160427311/ee1eba4c-45e1-49ce-8331-8335b139e7df"> <br>
Click "SLA Plan" <br>
<img width="573" alt="click SLA Plan" src="https://github.com/jaysixco/ticket-lifecycle-rd/assets/160427311/255e1eba-e67e-4ae2-9230-c46ddfdf442a">
<br>
Click Sev-A then click "Update" <br>
<img width="386" alt="image" src="https://github.com/jaysixco/ticket-lifecycle-rd/assets/160427311/1db83556-ca27-4fbe-a44f-72691eaa2bc5">
<br>

<strong> Part 4: Solve the ticket (Agent) </strong> <br>
Log out of Jay <br>
<img width="578" alt="image" src="https://github.com/jaysixco/ticket-lifecycle-rd/assets/160427311/0bf5e77e-64d2-4b1d-9e86-f765a8e68038">
<br>
Log in as the agent you reassigned the ticket to in part 2 <br>
<img width="243" alt="image" src="https://github.com/jaysixco/ticket-lifecycle-rd/assets/160427311/b8e3b9f6-0c41-41b1-be0d-f1354ca783fe">
<img width="575" alt="image" src="https://github.com/jaysixco/ticket-lifecycle-rd/assets/160427311/285afa5a-6a8b-477b-b9e0-b312e4a5e39b">
<br>
Click the ticket <br>
<img width="575" alt="image" src="https://github.com/jaysixco/ticket-lifecycle-rd/assets/160427311/ee1eba4c-45e1-49ce-8331-8335b139e7df"> <br>
Scroll down, write a response in the white box (1); for "Signature:" click "Department Signature (support) (2), change "Ticket Status:" to "Resolved" (3); then click "Post Reply" (4) <br>
<img width="583" alt="image" src="https://github.com/jaysixco/ticket-lifecycle-rd/assets/160427311/38e8dcdc-9ba8-4ff2-891f-c7b70bd6d7ed">
<br>
Will automatically bring you to tickets page. You can see that the ticket is no longer in que. <br>
<img width="576" alt="image" src="https://github.com/jaysixco/ticket-lifecycle-rd/assets/160427311/d861b52f-8f91-44a3-88bf-2d89d3254b58">
</p>

Done. Only thing left to do is to add red rectangles to the screenshots. 
P.S. 1 more screenshot left to get (of osTicket login page when logging in as admin) (get it when doing another trial run).












