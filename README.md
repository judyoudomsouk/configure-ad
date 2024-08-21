<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Setup resources in Azure
- Ensure connectivitiy between the client and Domain controller
- Install Active Directory
- Create an Admin and Normal User Account in AD
- Join Client-1 to your domain (mydomain.com)
- Setup Remote Desktop for non-administrative users on Client-1
- Create additional users and attempt to login client-1 with one of the users

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/X9gt17J.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Adding additional users to Active Directory Users and Computers in Domain controller .
</p>
<br />

<p>
<img src="https://i.imgur.com/AFx4NoL.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Creating additional users in Domain controller Active Directory Users and Computers.
</p>
<br />

<p>
<img src="https://i.imgur.com/tuqZQA7.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Attempt to login in client-1 with one of the users.
</p>
<br />
