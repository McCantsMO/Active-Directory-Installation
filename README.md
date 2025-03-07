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

- Step 1: Create a Virtual Machine/Resource Group.
- Step 2: Log into Virtual Machine
- Step 3: Install Active Directory Domain Services.
- Step 4

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/t4e2hdB.png) height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here, I open Server Manager and run it as an Administrator.  
</p>
<br />

<p>
<img src="https://i.imgur.com/JHyVTGs.png) height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In Server Roles, I activate the Active Directory Domain Services that has already been installed.
</p>
<br />

<p>
<img src="https://i.imgur.com/nWWfTfH.png) height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I open Active Directory Computers and Users window. In that window, I click on the 'mydomain.com' folder and Organizational Unit folders: _Clients, _Admins, and _Employees.
</p>
<br />

<p>
<img src="https://i.imgur.com/VmQk9RE.png) height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I create users to add to my folders, in this case, it is Jane Doe.
</p>
<br />

<p>
<img src="https://i.imgur.com/7bykegy.png) height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I add Jane Doe to the Security Group, _Admins.
</p>
<br />

<p>
<img src="https://i.imgur.com/O4NVP6J.png) height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
