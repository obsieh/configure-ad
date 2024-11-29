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

- Step 1:Install Active Directory Domain Services (AD DS)
- Step 2: Promote the Server to a Domain Controller
- Step 3:Configure Organizational Units (OUs)
- Step 4: Add Users, Groups, and Computers
- step 5: Apply Group Policies

<h2>Deployment and Configuration Steps</h2>

Step 1: Install and Configure Active Directory

![image](https://github.com/user-attachments/assets/d32ac750-3139-404b-96e4-757ac84f9a32)

</p>
<p>
Install Active Directory Domain Services (AD DS) on the domain controller to create and configure a new domain. Restart the server and log in using domain credentials to finalize the setup.
</p>
<br />
Step 2: Create Administrative and Organizational Units

![image](https://github.com/user-attachments/assets/7f5bc082-f736-4656-b0bc-a4b3cc56ba47)

</p>
<
Use Active Directory tools to create Organizational Units (OUs) for grouping users and devices. Add an admin account to manage domain settings and assign appropriate permissions.


</p>
<br />
Step 3: Join a Client Machine to the Domain
  
![image](https://github.com/user-attachments/assets/3cd2db0b-0346-483d-9bb2-c83bfb8e3e71)

</p>
<p>
Join client computers to the domain by updating DNS settings and verifying their addition in Active Directory. Organize client machines into appropriate OUs for better management.
  
Step 4: Enable and Test Remote Desktop

![image](https://github.com/user-attachments/assets/38af091a-1dc8-4900-958f-1b115a300ac5)

Set up Remote Desktop for domain users on client machines. Create user accounts, assign them to the appropriate OUs, and test access to ensure proper connectivity and permissions.
  
</p>
<br />
