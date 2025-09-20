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
<img width="80%" height="80%" alt="OSTickLifecycle1" src="https://github.com/user-attachments/assets/0d0719aa-1d42-4889-aed9-9dcae340420b"/>
</p>

<h3>2.) Observe Ticket Properties as Help Desk Agent</h3>

- Log in as **Help Desk Agent (john)**.
- Observe the ticket’s properties:
  - **Priority:** Default value.
  - **Department:** Default department.
  - **SLA:** Default SLA.
  - **Assigned To:** Not yet assigned.
 
<p>
<img width="80%" height="80%" alt="OSTickLifecycle2" src="https://github.com/user-attachments/assets/903a5223-8a44-498b-9e5b-24de7ed49577" />
</p>

<h3>3.) Set Ticket Properties</h3>

- Update the ticket with the following properties:
  - **SLA:** Sev-A (1 hour, 24/7).
  - **Assigned To:** Online Banking Department.

<p>
<img width="80%" height="80%" alt="OSTickLifecycle3" src="https://github.com/user-attachments/assets/1515a041-2dbf-4130-b993-cc56013c3ef0" />
</p>

<h3>4.) Work the Ticket to Completion</h3>

- Log in as **Help Desk Agent (jane)**.
- Take ownership of the ticket, work the issue, and resolve it.
- Mark the ticket as **Closed** once the issue is resolved.

<p>
<img width="80%" height="80%" alt="OSTickLifecycle4" src="https://github.com/user-attachments/assets/bce1339a-025a-4c5a-b0b9-d2c305001624" />
</p>

<p>
<img width="80%" height="80%" alt="OSTickLifecycle5" src="https://github.com/user-attachments/assets/271a3060-640e-452e-956a-32f1e8a6f8c0" />
</p>

---

<h2>Conclusion</h2>

By following these steps, you have successfully demonstrated a very simplistic lifecycle of a ticket from intake to resolution within osTicket. This highlights the importance of ticket properties, proper assignment, and resolution processes in a help desk environment.
