<p align="center">
<img src="https://i.imgur.com/9PeLFEi.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps">

  
<h2> osTicket - Ticket Lifecycle: Intake Through Resolution</h2>
<p> Part 3 of this three-part osTicket tutorial series focuses on the ticket lifecycle, guiding you through the entire process—from ticket creation and intake to resolution—within the open-source helpdesk ticketing system, osTicket. This section demonstrates how tickets are managed, assigned, and resolved efficiently using the platform’s built-in features.</p>

<H2> Environments and Techologies Used </H2>
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2> Operating Systems Used </h2>
- Windows 10(21H2)

<h2>  Ticketing Lifecycle Stages </h2>
- Intake
- Assignment and Communication
- Working on the Issue
- Resolution

<h2> Stage 1: Intake - Creating a Ticket    </h2>
<P>Open osTicket to begin creating a new support ticket.

[If you need help with the initial setup, refer to Part 1 of this tutorial series](https://github.com/samaankw/osticket-prereqs)

[For configuration guidance, check out Part 2 of the series](https://github.com/samaankw/post-install-config).



Once you're in the system, click on Open a New Ticket and fill out the form with the following details:

Email Address: johnson@osTicket.com

Name: Keyana Johnson

Help Topic: Select Business Critical Outage from the dropdown menu

Issue Summary: The Entire mobile online banking is down

Details: Customers are reporting they are getting a 404 error when attempting to access online banking

After completing the form, click Create Ticket to submit the issue. </P>

<img src="https://i.imgur.com/rmqzJXn.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps">
<img src="https://i.imgur.com/NFWSHj5.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps">

<h2> Step 2: Assignment and Communication </h2>
<p>Log in to osTicket as an Agent using the credentials we created earlier for jane.doe.

Once you're signed in, navigate to the Tickets section and locate the ticket that was created in Step 1. Click on the ticket to open and view its details. </p>

<img src="https://i.imgur.com/h0M3mqk.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps">
<p>ince this is a business-critical incident, update the ticket with the following details:

Priority: Set to Emergency, as mobile online banking downtime can result in significant revenue loss.

Assigned To: Jane Doe

SLA Plan: Select SEV-A, given the severity and urgency of the issue.

Department: Assign to System Administrators, as they are responsible for the mobile banking infrastructure.

In the Response text box, enter the following message:

"Coordinating with the System Administrators team to bring mobile banking back online."

Once everything is filled out correctly, click Post Reply to update the ticket and begin resolution efforts. </p>



