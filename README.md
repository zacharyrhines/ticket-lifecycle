<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used</h2>

- Windows 10 (22H2)

<h2>Ticket Lifecycle Stages</h2>

1. **Intake**
2. **Assignment and Communication**
3. **Working the Issue**
4. **Resolution**

<h2>Lifecycle Stages</h2>

<h3>1.) Create Tickets as End-Users</h3>

 - **Scenario:** Create a ticket as an end-user with the following details:
  - **Subject:** "Entire mobile/online banking system is down"
  - **Details:** Describe the issue briefly (e.g., "The entire online banking system is down, preventing users from accessing their accounts.")

<p>
<img src="https://imgur.com/hSdHs1T.png" height="80%" width="80%" alt="Lab 3 Step 3"/>
</p>

<h3>2.) Observe Ticket Properties as Help Desk Agent</h3>

- Log in as **Help Desk Agent (john)**.
- Observe the ticket’s properties:
  - **Priority:** Default value.
  - **Department:** Default department.
  - **SLA:** Default SLA.
  - **Assigned To:** Not yet assigned.
 
<p>
<img src="https://imgur.com/t4yCX2B.png" height="80%" width="80%" alt="Lab 3 Step 3"/>
</p>

<h3>3.) Set Ticket Properties</h3>

- Update the ticket with the following properties:
  - **SLA:** Sev-A (1 hour, 24/7).
  - **Assigned To:** Online Banking Department.

<p>
<img src="https://imgur.com/XWmKN7q.png" height="80%" width="80%" alt="Lab 3 Step 3"/>
</p>

<h3>4.) Work the Ticket to Completion</h3>

- Log in as **Help Desk Agent (jane)**.
- Take ownership of the ticket, work the issue, and resolve it.
- Mark the ticket as **Closed** once the issue is resolved.

<p>
<img src="https://imgur.com/cUhLwqL.png" height="80%" width="80%" alt="Lab 3 Step 3"/>
</p>

<p>
<img src="https://imgur.com/OA3iMSL.png" height="80%" width="80%" alt="Lab 3 Step 3"/>
</p>

---

<h2>Conclusion</h2>

By following these steps, you have successfully demonstrated a very simplistic lifecycle of a ticket from intake to resolution within osTicket. This highlights the importance of ticket properties, proper assignment, and resolution processes in a help desk environment.
