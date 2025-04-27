<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

### 📍 [Part 1: Prerequisites & osTicket Installation](https://github.com/derickayala25/osticket-prereqs)
### 👉 [Part 2: Post-Installation Configuration](https://github.com/derickayala25/post-install-config)
### 👉 Part 3: Ticket Lifecycle Demo

</div>





<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to create, work, and resolves tickets within osTicket](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket (Help Desk Customer Support Software)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<b>Opening a New Ticket</b></br>
We will create a ticket as an end user. To do this, we will navigate to http://localhost/osTicket/. This will open the end-user support center.

1. Click on the blue `Open a New Ticket` button.
2. Required fields are <b>Email Address</b>, <b>Full Name</b>, <b>Help Topic</b>, and an <b>Issue Summary</b>.
3. The enduser will be Karen, her email is karen@enduser.com, and her issue is that the entire graphics department is unable to access Adobe Creative Cloud.
4. She will select the <b>Help Topic</b> <em>Report a Problem/Access Issue</em>.

<p>
<img src="https://github.com/user-attachments/assets/83e89bae-71ef-47e8-9bbb-735668d9a912" height="80%" width="80%" alt="New Ticket"/>
</p>

5. Once the information has been entered Karen will click the `Create Ticket` button and will receive a confirmation message.

<p>
<img src="https://github.com/user-attachments/assets/9ea1afb4-7b18-417c-8afc-1e6a53aee7a2" height="80%" width="80%" alt="New Ticket"/>
</p>

<b>Signing in as Administrator</b></br>
The administrator will sign it to osTicket using this link http://localhost/osTicket/scp/login.php. Karen's request will, by default, be</br>
directed to the <b>Support</b> department, which the administrator is a part of.

<p>
<img src="https://github.com/user-attachments/assets/0f120974-1e52-4921-b8ad-fe2bf5e2eb28" height="80%" width="80%" alt="Admin Open Tickets"/>
</p>


<b>Assigning the ticket to an Agent</b></br>
The administrator will assign Karen's ticket to John.
1. From the <b>Agent Panel</b> the Admin will open the ticket.
2. After reading the request, he will adjust, if necessary, the <b>Priority</b>, <b>SLA Plan</b>, <b>Assigned To</b> and <b>Department</b>.
3. This request will be updated to an <b>Emergency</b> and the <b>SLA Plan</b> will be updated to <em>Sev-A</em>.
4. Once that's done, go to <b>Assigned To:</b> and assign the ticket to John, as he's part of the <b>In-House Systems</b> team that handles these requests.

<p>
<img src="https://github.com/user-attachments/assets/9b6f5f19-3c97-48f2-96e5-94118b579cde" height="80%" width="80%" alt="Admin Open Tickets"/>
</p>

<b>Working the ticket as the Agent</b></br>
Log out as the administrator and log in as John. John will receive the ticket in his queue.</br>

<p>
<img src="https://github.com/user-attachments/assets/e2cf91d9-5761-4503-bc12-4f88de7d991b" height="80%" width="80%" alt="Admin Open Tickets"/>
</p>

After he takes inventory of the ticket details he can start looking for a resolution. He may post a reply to Karen detailing next steps or start looking for a resolution to the issue. John finds that a recent update has bugs that don't allow Adobe Creative
Suite to run. He rolls back the update and emails Karen, asking her if Adobe is working now.



![image](https://github.com/user-attachments/assets/a5cfd883-e08e-47c6-b2bf-69d6800d226b)


<b>Closing out the ticket</b></br>
Karen responds that everything's working correctly. John confirms receipt of the message and proceeds to close the ticket. In order to do this, he will write a response to Karen, change the <b>Ticket Status</b> from `Open (current)` to `Closed`. Then
he will click on the orange `Post Reply` button.

<p>
<img src="https://github.com/user-attachments/assets/278fddc1-5826-47ab-aa5c-ecec055668bf" height="80%" width="80%" alt="Admin Open Tickets"/>
</p>

<b>Ticket queue after closing out the request</b></br>
After posting the reply to Karen, osTicket will take John to the Open Tickets queue. Karen's request has been moved to the `Closed` tickets tab.

<p>
<img src="https://github.com/user-attachments/assets/93901f4b-019a-4ff0-8fb8-e936dfc73a95" height="80%" width="80%" alt="Admin Open Tickets"/>
</p> 

<p>
<img src="https://github.com/user-attachments/assets/2a865b63-d3dd-4fce-8c30-783ae49e2874" height="80%" width="80%" alt="Admin Open Tickets"/>
</p>

Joe also will be able to see it and see that it was closed by John.

<p>
<img src="https://github.com/user-attachments/assets/d8d7fda2-dbab-4d15-ac69-983754118de2" height="80%" width="80%" alt="Admin Open Tickets"/>
</p>

1. Click on the blue `Open a New Ticket` button.
2. Required fields are <b>Email Address</b>, <b>Full Name</b>, <b>Help Topic</b>, and an <b>Issue Summary</b>.
3. The enduser will be Karen, her email is karen@enduser.com, and the entire graphics department is unable to access Adobe Creative Cloud.
4. She will select the <b>Help Topic</b> <em>Report a Problem/Access Issue</em>.




![image](https://github.com/user-attachments/assets/5df82cbc-c43f-4a34-bd97-3cdac12e8a7b)

![image](https://github.com/user-attachments/assets/dcef1cb2-7aff-4bbe-89af-155de754f19f)

![image](https://github.com/user-attachments/assets/e409e4ac-2435-4ae2-a525-d6f3c8e6ca53)

![image](https://github.com/user-attachments/assets/e069a890-cc62-4d3d-bf87-389eda2846ed)

![image](https://github.com/user-attachments/assets/d47839f3-74c3-49ab-b9fd-bf3a5e76fc8a)

![image](https://github.com/user-attachments/assets/31b44a78-0f62-46b5-a041-24240992c022)

![image](https://github.com/user-attachments/assets/d3c99319-4019-4720-adad-15a0aff676c5)







<p align="center">
  <a href="https://github.com/drewmarsh/osTicket-ticket-lifecycle-demo">
    <img src="/images/osticket-banner.png" width="598" alt="Banner">
  </a>
</p>

<div align="center">

### 👉 [Part 1: Prerequisites & osTicket Installation](https://github.com/drewmarsh/osTicket-installation)
### 👉 [Part 2: Post-Installation Configuration](https://github.com/drewmarsh/osTicket-post-install-configuration)
### 📍 Part 3: Ticket Lifecycle Demo

</div>





# 🧠 Technologies Used
- osTicket (Help Desk Ticketing System)
- Microsoft Azure (Cloud Computing)
- Remote Desktop
- Windows 10 Professional x64 22H2

# 📝 Ticket Lifecycle Stages
- Intake
- Assignment & Communication
- Working the Issue
- Resolution

# ♻️ Ticket Lifecycle Examples: From Intake to Resolution

### 📩 Intake
1. Navigate to `localhost/osTicket/index.php` and click the blue `Open a New Ticket` button.

<img src="/images/open-new-ticket.png" alt="Open New Ticket">

2. Proceed to fill out the following fields with the relevant ticket information:
    - **Email Address**: The email address of whoever is submitting the ticket
    - **Full Name**: The full name of whoever is submitting the ticket
    - **Help Topic**: Click on the drop-down menu and select the issue that best fits with the issue in which the ticket is regarding
    - **Issue Summary** In the first field, enter a brief title for the issue and then proceed to the second field where a more detailed description is optional but recommended

In the end-user-created ticket example below, `Jane Doe` (best reached at `jane.doe1999@gmail.com` or `999-999-9999`) is submitting a ticket regarding her trouble to access online mobile banking.

<img src="/images/end-user-ticket.png" alt="End User Ticket">

### 💬 Assignment & Communication
1. Navigate to `localhost/osTicket/scp/login.php` and enter the credentials for the administrator that will assign an Agent to work on the ticket created during Intake.

<img src="/images/admin-credentials.jpg" alt="Admin Credentials">

2. Navigate to `Tickets` > ` Open` and then open the ticket by clicking the ticket number under the **Ticket** column.

<img src="/images/open_ticket_as_admin.png" alt="Open Ticket as Admin">

3. From here, set the **Priority**, **Assign Department**, **Assigned To**, and the **SLA Plan** values for this ticket.

In the example below, the admin first clicks on the greyed out `— Unassigned —` text that's located to the right of **Assigned To**. Then, the admin designates `Luke Skywalker` as the **Assignee**.

<img src="/images/assign-agent-to-ticket.png" alt="Assign Agent to Ticket">

After the agent has been assigned to this particular ticket, the admin sets the **Priority** to `High`, the **Department** to `Support`, and the **SLA Plan** to `SEV-A`.

<img src="/images/filled-ticket-info.png" alt="Filled Ticket Info">

4. Within the ticket tab, you can see the thread of any updates to the ticket and submit updates upon assignment. Once finished, click the orange `Post Reply` button and the ticket gets assigned to the appropriate department and your customer gets notified of this change.

<img src="/images/ticket-timeline.png" alt="Ticket Timeline">

### 🛠️ Working the Issue
1. Navigate to `localhost/osTicket/scp/login.php` and enter the credentials for the Agent that has been assigned to work on the ticket created during Intake.

<img src="/images/agent-credentials.png" alt="Agent Credentials">

2. Once logged in, the Tickets window shows. It will show the ticket number, the last time it was updated, the subject, who submitted the ticket, priority level, and who it is assigned to. The Agent must click on the ticket number to open it so that they can begin working through the problem.

<img src="/images/tickets-window.png" alt="Tickets Window">

3. Once the ticket is opened, you can review all ticket items and the history of the ticket items. This includes who submitted the ticket, who assigned the ticket, and any other ticket activity. The bottom section is where you can leave a reply for the user who submitted the ticket and an internal note to notify management if the ticket has been resolved.

<img src="/images/opened-ticket.png" alt="Opened Ticket">

4. Once the Agent (Luke Skywalker) has reviewed all of the ticket details and identified a solution to the problem, the Agent can then use the **Post Reply** section to write a note to the user (Jane Doe) explaining everything, including the solution, in a professional manner.

<img src="/images/agent-works-the-issue.png" alt="Agent Works the Issue">

### ❤️‍🩹 Resolution

1. Before the user presses the orange `Post Reply` button to send the message to the user, it is important to navigate to the **Ticket Status** drop-down menu and change the value from `Open (current)` to `Closed`.

<img src="/images/close-the-ticket.png" alt="Close the Ticket">

2. Then, osTicket will take the Agent back to the Tickets tab. The Agent will then see a confirmation that the reply was posted successfully. As pictured below, ticket `#325542` by Jane Doe is no longer showing in the **Open** tickets section. Additionally, there is a visual confirmation banner at the top that says `Ticket #325542: Reply posted successfully`.

<img src="/images/ticket-closed-confirmation.png" alt="Ticket Closed Confirmation">

3. To view tickets that have been closed, Agents can navigate to `Tickets` > `Closed` > and then click the appropriate time frame that this ticket is from. From here, the Agent should see closed ticket in question.

<img src="/images/viewing-closed-ticket.png" alt="Viewing Closed Ticket">

<br><div align="center">

### 👉 [Part 1: Prerequisites & osTicket Installation](https://github.com/drewmarsh/osTicket-installation)
### 👉 [Part 2: Post-Installation Configuration](https://github.com/drewmarsh/osTicket-post-install-configuration)
### 📍 Part 3: Ticket Lifecycle Demo

</div>
