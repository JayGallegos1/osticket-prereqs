<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br/>


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2) </br>

<h2>List of Prerequisites</h2>

- Create Resource Group
- Create Windows 10 Virtual Machine with 2-4 Virtual CPUs
- Allow VM to create Virtual Network and Subnet

<h2>Installation Steps</h2>

<p align="center">
Enable IIS in Windows: 
</br>
<img src="https://imgur.com/HvQtK9n.png" height="80%" width="80%" alt="osTicket Steps"/>
</p>
</br>

<p align="center">
Install Web Platform Installer:
</br>
<img src="https://imgur.com/YrRSYbq.png" height="80%" width="80%" alt="osTicket Steps"/>
</p>
</br>

<p align="center">
Add MySQL 5.5:
</br>
<img src="https://imgur.com/iA44ueV.png" height="80%" width="80%" alt="osTicket Steps"/>
</p>
</br>

<p align="center">
Istall PHP 5.631 (x86) - PHP 7.3.25 (x86):
</br>
<img src="https://imgur.com/NJCXsmf.png" height="80%" width="80%" alt="osTicket Steps"/>
<img src="https://imgur.com/XtzXAez.png".png" height="80%" width="80%" alt="osTicket Steps"/>
<img src="https://imgur.com/OCKxO0q.png" height="80%" width="80%" alt="osTicket Steps"/>
</p>
</br>

<p align="center">
Intall Microsoft C++:
</br>
<img src="https://imgur.com/nHnXKWX.png" height="80%" width="80%" alt="osTicket Steps"/>
</p>
</br>

<p align="center">
Download osTicket, extract and copy “upload” folder into c:\inetpub\wwwroot
and rename upload folder to osTicket:
</br>
<img src="https://imgur.com/MIaTrj2.png" height="80%" width="80%" alt="osTicket Steps"/>
<img src="https://imgur.com/EQ661eA.png" height="80%" width="80%" alt="osTicket Steps"/>
<img src="https://imgur.com/coOdOhL.png" height="80%" width="80%" alt="osTicket Steps"/>
</p>
</br>

<p align="center">
Open IIS, go to sites -> Default -> osTicket, then click Browse 80:
</br>
<img src="https://imgur.com/CgYbPdr.png" height="80%" width="80%" alt="osTicket Steps"/>
</p>
</br>

<p align="center">
Go to IIS, sites -> Default -> osTicket. Enable php_imap.dll, php-intl.dll, and php_opcache.dll:
</br>
<img src="https://imgur.com/TQLeGO6.png" height="80%" width="80%" alt="osTicket Steps"/>
<img src="https://imgur.com/SNX8kE0.png" height="80%" width="80%" alt="osTicket Steps"/>
</p>
</br>


<p align="center">
Select C:\inetpub\wwwroot\osTicket\include\ost-sampleconfig.php: 
<img src="https://imgur.com/DFLIL2R.png" height="80%" width="80%" alt="osTicket Steps"/>
</p>
</br>

<p align="center">
Rename it to C:\inetpub\wwwroot\osTicket\include\ost-config.php:
<img src="https://imgur.com/CxhxuKN.png" height="80%" width="80%" alt="osTicket Steps"/>
</p>
</br>

<p align="center">
Disable inheritance for ost-config.php, enable Everyone full control:
<img src="https://imgur.com/5rMjM24.png" height="80%" width="80%" alt="osTicket Steps"/>
<img src="https://imgur.com/I3NooOQ.png" height="80%" width="80%" alt="osTicket Steps"/>
</p>
</br>

<p align="center">
Download and install HeidiSQL:
<img src="https://imgur.com/zI5y5K1.png" height="80%" width="80%" alt="osTicket Steps"/>
</p>
</br>

<p align="center"> 
Create a new session:
</p>
<p align="center">
<img src="https://imgur.com/joi73Dt.png" height="80%" width="80%" alt="osTicket Steps"/>
</p>
</br>

<p align="center">
Create a database named "osTicket":
<img src="https://imgur.com/6winqJg.png" height="80%" width="80%" alt="osTicket Steps"/>
</p>
</br>
 
<p align="center">
Click "Install Now!" :
</p>
<p align="center">
<img src="https://imgur.com/p8aBCwg.png" height="80%" width="80%" alt="osTicket Steps"/>
</p>
</br>

<p align="center">
Delete: C:\inetpub\wwwroot\osTicket\setup:
<img src="https://imgur.com/1frDWPf.png" height="80%" width="80%" alt="osTicket Steps"/>
</p>
</br>

<p align="center">
Set Permissions to “Read” only: C:\inetpub\wwwroot\osTicket\include\ost-config.php:
<img src="https://imgur.com/K6I843U.png" height="80%" width="80%" alt="osTicket Steps"/>
</p>
</br>

<p align="center">
Login to the osTicket Admin Panel.
<img src="https://imgur.com/gXYyAHF.png" height="80%" width="80%" alt="osTicket Steps"/>
<img src="https://imgur.com/O7bhYBQ.png" height="80%" width="80%" alt="osTicket Steps"/>
</p>
</br>



