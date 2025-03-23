# configure-ad

<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploy on-premises Active Directory within Azure Compute](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Set Domain Controller in Azure
- Set up client in Azure
- Connect to the VM's


<h2>Deployment and Configuration Steps</h2>

![image](https://github.com/user-attachments/assets/48b91c75-4238-4b05-85d3-0ac69124f902)

</p>
<p>
 - Set up the VM's for the lab
</p>
<br />

![image](https://github.com/user-attachments/assets/05267ed8-833a-4d98-bace-8326abd07bb0)

</p>
<p>
 - Install Active Directory Domain Services on dc1
</p>
<br />

![image](https://github.com/user-attachments/assets/2d971e16-ef4d-4984-93cb-564f9f7e1dd1)

</p>

  - Create an Organizational Unit called “_EMPLOYEES”
  - Create a new OU named “_ADMINS”
  - Create a new employee 
</p>
<br />


![image](https://github.com/user-attachments/assets/5508cef9-6341-46cb-9e3c-e3c0651317f9)

</p>
<p>
 - Allow domain users access to remote desktop on client 1

</p>
<br />


![image](https://github.com/user-attachments/assets/223e3383-d8c7-4e84-9a53-b0fd5dd532c8)
![image](https://github.com/user-attachments/assets/f85d0219-c896-44c4-a85a-59c88062d5a8)

</p>

 - Open powershell as an admin
  - Create a new file and paste the contents of the script into it
  - log into a user in client vm
</p>
<br />

