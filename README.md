# Active-Directory-Deployment-Lab

This tutorial outlines the set Up and deplyoment active directory and account creation within a practice enviorment.<br />

<h2>Environments and Technologies Used</h2>
- Microsoft Azure Virtual Machines
- Windows Datacenter 2022 Azure Center
- Windows 11
- Azure Resource Group
- Active Directory


1. Create a Resource Group


2. Create a VM (This VM will be our Domain Controler)


3. Create a second VM (This will be your Client 1)


4. Make the Domain Controller's private IP address static > Then with Client 1 ping Domain Controler VM


5. Instal Active Directory on the DC VM


6. Create an Admin and Normal User Account in AD


7. Join Client-1 to your domain (mydomain.com)


8. Setup Remote Desktop for non-administrative users on Client-1


9. Create a bunch of additional users and attempt to log into client-1 with one of the users

# -----------

<h2>Deployment</h2>

<p align="center">
<img src="https://i.imgur.com/xDSVm7Z.png" alt="Creation Of Resource Group"/>

<p align="center">
<img src="https://i.imgur.com/2iAWuAq.png" alt="Creation Of Domain Controler"/>

<p align="center">
<img src="https://i.imgur.com/RYzZ1lp.png" alt="Creation Of Client 1 VM"/>

<p align="center">
<img src="https://i.imgur.com/9o9P7Ni.png" alt="Make IP address static"/>

<p align="center">
<img src="https://i.imgur.com/IwdotRE.png" alt="Login into DC VM and install Active Directory Services"/>

<p align="center">
<img src="https://i.imgur.com/I4Le1zt.png" alt="Create an admin account and OU's"/>

<p align="center">
<img src="https://i.imgur.com/ogLhCgx.jpeg" alt="Login into Jane Admin account (on Client-1), then join it to mydomain.com"/>

<p align="center">
<img src="https://i.imgur.com/A5ntIP4.png" alt="Setup Remote Desktop for non-administrative users, then run Powershell script in DC VM as adminstrator"/>

<p align="center">
<img src="https://i.imgur.com/2d5hPQF.png" alt="The scrpit will have created additional users
"/>





