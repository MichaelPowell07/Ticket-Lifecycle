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

1.) Scenario 1: Create a ticket as an end user with the following details.
- Subject: "Entire mobile/online banking system is down"
- Details: Describe the issue briefly (e.g., "The entire online banking system is down,preventing users from accessing their accounts".)

  ![image](https://github.com/user-attachments/assets/7ca6f51f-e7d9-400e-84ca-e34b87fcdb69)

2.) Observe Ticket Properties as Help Desk Agent
-Login as Help Desk Agent (John).
- Observe the tickets properties
- Priority: Default value
- Department: Default department.
- SLA: Default SLA
- Assigned to: Not yet assigned.

![image](https://github.com/user-attachments/assets/d0f26503-c5d5-4933-8656-7d67d751f93d)

3.) Set Ticket Properties
- Update the ticket with the following properties
- SLA: Sev-A ( 1Hour,24/7).
- Assigned to: Online banking Department.
  
![image](https://github.com/user-attachments/assets/407f7b9c-395d-4dd9-bafa-1a7bfb6a4c8b)

4.) verify Ticket Permissions
- Log back in as Help Desk Agent (John).
- Attempt to view or modify the ticket. Verify whether the changes are accessible or editable.

5.) Work the Ticket to Completion
-Login as Help Desk Agent (Jane).
- Take ownership of the ticket, work the issue and resolve it.
- Mark the ticket as closed once the issue is resolved.
  
![image](https://github.com/user-attachments/assets/3580a762-a58b-49de-9f80-843329503183)

![image](https://github.com/user-attachments/assets/62d6a40e-6b0d-4765-a857-abc0a221ea44)


6.) Create Another Ticket as End-user
-Scenario 2: Create a ticket as an end-user with the following details
- Subject: "Accounting department needs Adobe upgrade, broken"
- Details: Describe the issue briefly (e.g., "The Adobe software used by the accounting department is broken and needs an upgrade.")

![image](https://github.com/user-attachments/assets/09c0f609-2beb-4155-91d3-224aaf197238)

  7.) Observe Ticket Properties as Help Desk Agent
  - Login as Help Desk Agent (John).
  - Observe the tickets properties.
  - Priority: Default value.
  - Department: Default department.
  - SLA: Default SLA.
  - Assigned to: Not yet assigned.

    ![image](https://github.com/user-attachments/assets/16108176-fa63-4938-8d04-51866e5b19b5)

    8.) Set Ticket Properties
    - Update the ticket with the following properties
    - SLA: Sev-C (Business hours)
    - Department: Support

     ![image](https://github.com/user-attachments/assets/e30fa4cb-b5a7-4aac-883b-dee5cea5ff86)

    9.) Work the Ticket to Completion
    - login as Help Desk Agent (John).
    - Take ownership of the ticket, work the issue and resolve it.
    - Mark the ticket as closed once the issue is resolved.

      ![image](https://github.com/user-attachments/assets/f6758385-4e34-421c-bf94-dc06dc5e2a16)

      ![image](https://github.com/user-attachments/assets/e72c7c70-5f03-4c88-995a-5dabb5b773f6)

      10.) Create a Final Ticket as End- user
      -Scenario 3: Create a ticket as an end-user with the following details.
      - Subject: "CFO's laptop will no longer turn on"
      - Details: Describe the issue briefly (e.g., "The CFO's is not powering on, and it needs urgent attention.")

        ![image](https://github.com/user-attachments/assets/557a2651-c3c1-4840-b3e2-1da12518e30f)

        11.) Observe Ticket Properties as Help Desk Agent
        -login as Help Desk Agent (John).
        -Observe the Tickets properties.
        -Priority: Default value.
        -Department:Default department.
        -SLA: Default SLA.
        -Assigned to: Not yet assigned.

        ![image](https://github.com/user-attachments/assets/a9e7c4e2-58be-4b58-9d81-31f6480b75ca)

        12.) Set Ticket properties
        - Update the ticket with the following properties
        - SLA: Sev-B (4Hours,24/7).
        - Department: Support.

          ![image](https://github.com/user-attachments/assets/85eaf9d2-0fc3-4080-9e2c-60f4a9161487)

          13.) Work the Ticket to Completion
          - Login as Help Desk Agent (John)
          - Take ownership of the Ticket, work the issue and resolve it.
          - Mark the ticket as closed once the issue is resolved.

            ![image](https://github.com/user-attachments/assets/d1b4226a-1ddf-466b-bcc0-326f24f6bed3)

            ![image](https://github.com/user-attachments/assets/430ec54c-7f28-413b-baaa-43ad11aad8f8)

            Conclusion

            By following these steps, you have successfully showed the lifecycle of a ticket from the intake to resolution within osTicket. This lab highlights the importance of ticket properties, proper assignment, and the resolution process in a help desk enviornment.







 

