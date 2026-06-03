<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>
<h2>Demonstration</h2>
<p>
<img width="720" height="627" alt="Screenshot 2026-06-03 152237" src="https://github.com/user-attachments/assets/50f9a9fc-5d9c-4493-ba1f-f82e7e971596" />

</p>
<p>
  User submits a request and osTicket automatically creates a ticket ID, sends confirmation email to user, and places the ticket in the queue
</p>
<br />
<p>
<img width="740" height="541" alt="Screenshot 2026-06-03 153422" src="https://github.com/user-attachments/assets/c7fd085b-277e-4ff0-9824-8821623c7fb1" />

</p>
<p>
Help desk agent recieves the assignment and sets the ticket to a department in this case the department is IT Support because we are dealing with password/ credentials. After we set the SLA plan which is the Service Level Agreement or the target that you have to meet for certain things, the Severity or priorty of the ticket in this case is normal
</p>
<br />

<p>
<img width="728" height="570" alt="Screenshot 2026-06-03 155333" src="https://github.com/user-attachments/assets/953e59db-56d8-4514-a358-b829df055870" />

</p>
<p>
Then we have the initial response to the user contacting them to get more information on the issue. The next step is to investigate and trouble shoot, checking account status and confirming the identity of the user before unlocking the account and resetting the password to ensure there is no supicious activity
</p>
<br />

 <img width="725" height="536" alt="Screenshot 2026-06-03 160142" src="https://github.com/user-attachments/assets/d1af76cd-2723-41d8-8adf-95769976ffce" />


The last step is the resolution and ticket closure, agent updates ticket and contacts user
