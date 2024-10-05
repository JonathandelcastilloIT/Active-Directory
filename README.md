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

(Step 1 overview) 

- I will configure and interconnect two virtual machines, each assuming distinct roles. The first virtual machine will be designated as the Domain Controller. The second virtual machine will be configured as the Client.

![image](https://github.com/user-attachments/assets/e9d78826-d6ae-4a80-98f2-19b1f67bfe15)

<h2></h2>

1. Create two VMs (Azure)in the same VNET. One will be a Domain Controller, the other will be a Client machine.

- Create a virtual machine (Domain Controller)on Azure.
- Name it DC-01
- Select Windows Server 2022: Azure Edition - x64 Gen2 as the image
- size    (Standard_D2s_v3 - 2 vcpus, 8 GiB memory)
- Create a username and password for your VM DC-1
![image](https://github.com/user-attachments/assets/2341bf39-8667-420b-953f-caeb221df308)


2. Create a virtual machine this will be our client machine

- Once again create a new VM and
- name it Client-01.
- select Windows 10 pro as the image
- select at least 2 vcpus and 16 GiB memory.
- Make sure to select the same resource group and Virtual networkfrom the DC-01 VM

![image](https://github.com/user-attachments/assets/d592b6eb-f3e6-4410-88da-555c82419bbb)















- Step 2
- Step 3
- Step 4

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
