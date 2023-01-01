<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Create Resource Group
- Create Windows 10 Virtual Machine with 2-4 Virtual CPUs

<h2>Installation Steps</h2>
<p>
Enable IIS in Windows.
</p>
<p>
<img src="https://imgur.com/HvQtK9n.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Install Web Platform Installer.
</p>

<p>
<img src="https://imgur.com/YrRSYbq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />
<p>
Add MySQL 5.5.
</p>
<p>
<img src="https://imgur.com/iA44ueV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Then you need to install PHP 5.631 (x86) - PHP 7.3.25 (x86).
</p>
<p>
<img src="https://imgur.com/NJCXsmf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<p>
<img src="https://imgur.com/XtzXAez.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://imgur.com/OCKxO0q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Intall Microsoft C++.
 </p>
<p>
<img src="https://imgur.com/nHnXKWX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<p>
Download osTicket, extract and copy the “upload” folder into c:\inetpub\wwwroot
and rename upload folder to osTicket.
 </p>
<p>
<img src="https://imgur.com/MIaTrj2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://imgur.com/EQ661eA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>


<p>
<img src="https://imgur.com/coOdOhL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Open IIS, go to sites -> Default -> osTicket, then click Browse 80.
</p>

<p>
<img src="https://imgur.com/CgYbPdr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Go to IIS, sites -> Default -> osTicket. Enable php_imap.dll, php-intl.dll, and php_opcache.dll.
</p>
<p>
<img src="https://imgur.com/TQLeGO6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://imgur.com/SNX8kE0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>


<p>
Rename C:\inetpub\wwwroot\osTicket\include\ost-sampleconfig.php to C:\inetpub\wwwroot\osTicket\include\ost-config.php
</p>


<p>
<img src="https://imgur.com/DFLIL2R.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://imgur.com/CxhxuKN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>



<p>
 Disable inheritance for ost-config.php, enable Everyone full control. 
</p>

<p>
<img src="https://imgur.com/5rMjM24.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://imgur.com/I3NooOQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
 Download and install HeidiSQL. 
</p>

<p>
<img src="https://imgur.com/zI5y5K1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>


<p>
Create a new session. 
</p>

<p>
<img src="https://imgur.com/joi73Dt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Create a database named "osTicket". 
</p>
<p>
<img src="https://imgur.com/6winqJg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 
</p>
Click "Install Now!"
<p>
<img src="https://imgur.com/p8aBCwg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Delete: C:\inetpub\wwwroot\osTicket\setup
</p>

<p>
<img src="https://imgur.com/1frDWPf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Set Permissions to “Read” only: C:\inetpub\wwwroot\osTicket\include\ost-config.php
</p>
<p>
<img src="https://imgur.com/K6I843U.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Login to the osTicket Admin Panel 
</p>
<p>
<img src="https://imgur.com/gXYyAHF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://imgur.com/O7bhYBQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

