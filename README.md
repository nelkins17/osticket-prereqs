<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.</br> 

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- Download to <a href="https://drive.google.com/drive/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6?usp=share_link">programs</a>


<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Microsoft Azure Account
- Microsoft Azure Subscription (At the time of writing this a free $200 credit trial is available)
- Programs linked above in Google Drive:
  - osTicket v1.15.8
  - PHP Manager
  - My SQL 5.5 Database
  - HeidiSQL Client


<h2>Overview of Installation Steps</h2>

- Create Virtual Machine in Azure
- Install osTicket Prerequisites
- Configure IIS
- Install osTicket
- Download and HeidiSQL and install
- Create a resource group in Azure
- Create a virtual machine in Azure and login to the vm with Remote Desktop
- Install and enable IIS in Windows
- Download and install PHP Manager for IIS
- Download and install Rewrite Module
- Download and install PHP
- Download and install VC
- Download and install MySQL
- Open IIS as admin and register PHP in IIS
- Download and install osTicket
- Enable extensions in IIS
- Assign permissions
- Download and install HeidiSQL
- Continue setting up osTicket in browser

<p align="center">
<img src="https://i.imgur.com/8ncjtlI.png" alt="osTicket Diagram"/>

<h2>Installation Steps</h2>

<p>
1. Create a resource group in Azure.
<br>
<img src="" height="80%" width="80%" alt="Step 1"/>
</p>
<br />

<p>
2. Create a virtual machine(VM) in Azure with a login.  **Remember your login**
<br>
<img src="" height="80%" width="80%" alt="Step 2"/>
</p>
<br />

<p>
3. Grab the public IP of the VM which you just created.
<br>
<img src="" height="80%" width="80%" alt="Step 3"/>
</p>
<br />

<p>
4. Download and install PHP Manager for IIS.
<br>
<img src="" height="80%" width="80%" alt="Step 4"/>
</p>
<br />

<p>
5. Download and install Rewrite Module.
<br>
<img src="" height="80%" width="80%" alt="Step 5"/>
</p>
<br />

<p>
6. Download and install PHP.
<img src="" height="80%" width="80%" alt="Step 6"/>
</p>
<br />

<p>
7. Download and install VC.
<br>
<img src="" height="80%" width="80%" alt="Step 7"/>
</p>
<br />

<p>
8. Download and install MySQL.
<br>
<img src="" height="80%" width="80%" alt="Step 8"/>
</p>
<br />
