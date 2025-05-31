<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- https://m.youtube.com/watch?v=OYoj_jJT4s8&pp=ygU2Q29uZmlndXJpbmcgb24gcHJlbWlzZSBhY3RpdmUgZGlyZWN0b3J5IGVpdGggYXp1cmUgdm1z

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Prepare Active Directory Infrustructure in Azure
- Deploy Active Directory
- Create Users in Powershell
- Configure Group Policy and manage accounts

<h2>Deployment and Configuration Steps</h2>

<p>

![image](https://github.com/user-attachments/assets/29e2ee10-17a7-49d6-961c-f64bbb8a0c93)



</p>
<p>
I am in the process of configuring my virtual machine for the Active Directory lab environment. At this stage, I have updated the IP address settings from dynamic to static to ensure consistent network communication. The screenshot shown captures the step where I temporarily disabled the firewall for controlled testing purposes."
</p>
<br />

<p>

  
  ![image](https://github.com/user-attachments/assets/c0b14cee-f4dc-42ce-b166-6de27c10d895)


</p>
<p>
For this lab, I configured two separate virtual machines. In this step, I am using PowerShell and the ipconfig /all command to verify the DNS settings. This is to ensure that the configuration correctly reflects the private IP address of the second virtual machine.
</p>
<br />

<p>

  ![image](https://github.com/user-attachments/assets/fec60c69-408f-4404-98ee-37ce7ea8e791)

</p>
<p>
  After setting up Active Directory Users and Computers, I utilized a PowerShell script to create over 1,000 user accounts. The objective was to ensure that each account was accurately placed within the appropriate Organizational Unit (OU) for proper structure and management.
</p>
<br />
