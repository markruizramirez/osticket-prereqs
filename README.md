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

- Create an Azure Virtual Machine Windows 10
- Within the VM download the osTicket-Installation-Files.zip
- Install / Enable IIS in Windows
- Open IIS as an Admin
- Install osTicket v1.15.8

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/LdNuSIO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Within the virtual machine, I downloaded the osTicket installation file and unzipped it to the desktop. Here I used the files within the folder to install osTicket and some of its dependencies.
</p>
<br />

<p>
<img src="https://i.imgur.com/fglUThq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here I had to enable IIS in windows which would be necessary to execute the rest of the installation process. From the installation folder, I had to install MySQL and execute the setup. Within IIS I enabled some extensions to configure the osTicket browser.
</p>
<br />

<p>
<img src="https://i.imgur.com/iC7MB15.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After enabling the required extensions from osTicket, I then had to install HeidiSQL, create a new session, and connect to the session. I continued to set up osTicket utilizing the MySQL database. Finally I was able to browse the help desk login page as an admin and as a end user. 
</p>
<br />
