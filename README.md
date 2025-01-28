<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Email Settings
- Set Permissions & User Roles
- Secure osTicket Installation
- Customize Ticketing System Settings
- Backup & Maintenance Plans

<h2>Configuration Steps</h2>

<p>
[<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>](https://i.imgur.com/HtuWj0O.png)
</p>
<p>
Configure Email Settings (SMTP & Incoming Email)
Why it's important: Email notifications are critical for ticketing systems. You need osTicket to send notifications to users and agents about ticket updates, responses, and alerts. Also, enabling email fetching (IMAP/POP3) allows you to create tickets directly from incoming emails.
What to do:
Set up SMTP to allow osTicket to send emails.
Configure an email inbox to fetch incoming emails (optional, but useful for automatic ticket creation).
</p>
<br />

<p>
[<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>](https://i.imgur.com/rJ4mkov.png)
</p>
<p>
Secure osTicket Installation
Why it's important:
  Security is essential to protect sensitive data. Without securing the system, it may become vulnerable to unauthorized access and attacks.
What to do:
Remove the installation directory (setup/ folder) to prevent attackers from running installation scripts again.
Set file permissions properly on important directories like attachments/ and include/ to prevent unauthorized access.
Enable SSL/HTTPS to ensure encrypted communication between users and the server.
</p>
<br />

<p>
[<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>](https://i.imgur.com/FYn2343.png)
</p>
<p>
Set Permissions & User Roles
Why it's important: Different users need different levels of access. You must define clear roles to prevent unauthorized access to sensitive admin sections and to ensure agents can work with tickets efficiently.
What to do:
Configure user roles like Admin, Agent, and End-User.
Assign permissions that control access to ticket management, reporting, settings, and admin functionalities.
</p>
<br />
