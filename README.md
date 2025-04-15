<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- Notepad/Notes App (Needed for saving usernames and passwords)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Prerequisites before simulating lab</h2>

<strong>- Before starting lab, delete the maintenance department</strong>

<strong>- Change the SysAdmins Department to a Top Level Department</strong>

<h2>Lifecycle Stages</h2>

<p>
<img src="https://i.imgur.com/M1OKgFS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
     <h3>Creating a Support Ticket(As A User Named Karen)</h3>
<ol>
    <li>Navigate to the <strong>Support Center</strong> of the helpdesk.</li>
    <li>Select the option to create a new ticket.</li>
    <li>Enter the required information:
        <ol>
            <li><strong>Email Address:</strong> karen@lognpacific.com</li>
            <li><strong>Full Name:</strong> Karen</li>
            <li><strong>Phone Number:</strong> 738-290-2412 (Fake Number)</li>
            <li><strong>Help Topic:</strong> Report a Problem</li>
            <li><strong>Issue Summary Title:</strong> Entire mobile/online banking system is down</li>
            <li><strong>Issue Summary:</strong> "My employees report that users can no longer access the online banking portal. Those who can occasionally access it are unable to log in."</li>
        </ol>
    </li>
    <li>Review all entered details for accuracy.</li>
    <li>Click <strong>Create Ticket</strong> to finalize the request.</li>
</ol>
</p>
<br />

<p>
<img src="https://i.imgur.com/7WRjzbq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
     <h3>Solving and Closing Previous Ticket(Online Banking Portal)</h3>
<ol>
    <li><strong>Log Out and Re-Login as an Agent</strong>
        <ol>
            <li>Log out of the Admin account.</li>
            <li>Log in as one of the agents.</li>
        </ol>
    </li>
    <li><strong>Review the Ticket</strong>
        <ol>
            <li>Locate and open the assigned support ticket.</li>
            <li>Review the ticket details for accuracy and completeness.</li>
        </ol>
    </li>
    <li><strong>Update the Ticket</strong>
        <ol>
            <li>Assign the <strong>SLA Plan</strong>: <em>Sev-A</em></li>
            <li>Provide a reason: <em>"Wide impact, customer unable to do online banking."</em></li>
            <li>Update the <strong>Help Topic</strong>: <em>Report a Problem / Business Critical Outage</em></li>
            <li>Provide a reason: <em>"No customers able to access online banking."</em></li>
        </ol>
    </li>
    <li><strong>Refresh the Page</strong>
        <ol>
            <li>Reload the webpage to confirm the ticket updates are visible.</li>
        </ol>
    </li>
    <li><strong>Respond and Resolve the Ticket</strong>
        <ol>
            <li>Once the online banking portal issue is resolved, return to the ticket.</li>
            <li>Reply to the ticket stating that the problem has been resolved.</li>
            <li>Change the ticket status to <strong>Resolved</strong>.</li>
        </ol>
    </li>
</ol>
</p>
<br />

<p>
<img src="https://i.imgur.com/jHhdHVT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
     <h3>Creating a Support Ticket(As A User Named Ken)</h3>
<ol>
    <li>Navigate to the <strong>Support Center</strong> of the helpdesk.</li>
    <li>Select the option to create a new ticket.</li>
    <li>Enter the required information:
        <ol>
            <li><strong>Email Address:</strong> ken@lognpacific.com</li>
            <li><strong>Full Name:</strong> Ken</li>
            <li><strong>Phone Number:</strong> 508-362-1104 (Fake Number)</li>
            <li><strong>Help Topic:</strong> General Inquiry/Other</li>
            <li><strong>Issue Summary Title:</strong> Accounting department needs adobe upgrade, broken</li>
            <li><strong>Issue Summary:</strong> "It looks like many people in the account department can't use their adobe software."</li>
        </ol>
    </li>
    <li>Review all entered details for accuracy.</li>
    <li>Click <strong>Create Ticket</strong> to finalize the request.</li>
</ol>
</p>
<br />

<p>
<img src="https://i.imgur.com/Ajafmb4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
     <h3>Solving and Closing Previous Ticket(Adobe Reader Upgrade)</h3>
<ol>
  <li>Log out of the admin account and log in as an agent.</li>
  <li>Navigate to the <strong>Tickets</strong> tab to review any new ticket requests.</li>
  <li>Once a new ticket is identified, open it and review the details for completeness and accuracy.</li>
  <li>If necessary, update the ticket with the correct information.</li>
  <li>Update the SLA Plan to <strong>Sev-C</strong> with the reason: 
    <ul>
      <li>"Only two users are unable to open Adobe Reader, which classifies the issue as Sev-C."</li>
    </ul>
  </li>
  <li>Post an initial reply with the following note: 
    <ul>
      <li>"The customer reports that only two individuals in the accounting department are unable to open and use Adobe Reader. The customer is attempting a restart and will follow up after lunch."</li>
    </ul>
  </li>
  <li>After the issue has been resolved, post a follow-up reply stating:
    <ul>
      <li>"The customer confirmed that a restart resolved the issue. Closing the ticket."</li>
    </ul>
  </li>
  <li>Set the ticket status to <strong>Resolved</strong> with the reason:
    <ul>
      <li>"Restart fixed the issue for both users."</li>
    </ul>
  </li>
</ol>
</p>
<br />

<p>
<img src="https://i.imgur.com/C7T3xFa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
     <h3>Creating a Support Ticket(As A User Named Karen Again)</h3>
<ol>
    <li>Navigate to the <strong>Support Center</strong> of the helpdesk.</li>
    <li>Select the option to create a new ticket.</li>
    <li>Enter the required information:
        <ol>
            <li><strong>Email Address:</strong> karen@lognpacific.com</li>
            <li><strong>Full Name:</strong> Karen</li>
            <li><strong>Phone Number:</strong> 738-290-2412 (Fake Number)</li>
            <li><strong>Help Topic:</strong> Report a Problem / Personal Computer Issues</li>
            <li><strong>Issue Summary Title:</strong> CFO's states he is unable to use laptop</li>
            <li><strong>Issue Summary:</strong> "Laptop won't power on, despite of pressing the power button"</li>
        </ol>
    </li>
    <li>Review all entered details for accuracy.</li>
    <li>Click <strong>Create Ticket</strong> to finalize the request.</li>
</ol>
</p>
<br />

<p>
<img src="https://i.imgur.com/8D50gNd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
      <h3>Solving and Closing Previous Ticket(CFOs Laptop)</h3>
<ol>
  <li>Log out of the admin account and log in as an agent.</li>
  <li>Navigate to the <strong>Tickets</strong> tab to review any new ticket requests.</li>
  <li>Once a new ticket is identified, open it and review the details for completeness and accuracy. Update any missing or incorrect information as needed.</li>
  <li>For this lab exercise:
    <ol>
      <li><strong>Set the Priority</strong> to <strong>Emergency</strong>.</li>
      <li><strong>Update the SLA Plan</strong> to <strong>Sev-B</strong>, with the reason:<br>
        <em>"May re-classify after obtaining more information."</em>
      </li>
      <li><strong>Assign the ticket</strong> to agent <strong>John Doe</strong>.</li>
    </ol>
  </li>
  <li>After the issue has been resolved, <strong>post a reply</strong> with the following note:<br>
    <em>"The CFO’s laptop was not charging due to a broken charger. A replacement charger was provided, and the laptop is now charging successfully."</em>
  </li>
  <li><strong>Set the ticket status to Resolved</strong> with the reason:<br>
    <em>"The charger was broken, which caused the battery to fully drain. This prevented the laptop from turning on."</em>
  </li>
</ol>
</p>
<br />
