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

- Create an Azure Virtual Machine Windows 10, 4 vCPUs
- Log into the VM with Remote Desktop
- Within the VM (osticket-vm), download the osTicket-Installation-Files.zip and unzip it onto your desktop. The folder should be called “osTicket-Installation-Files”
We will use the files in this folder to install osTicket and some of the dependencies.
- Install / Enable IIS in Windows WITH CGI
World Wide Web Services -> Application Development Features -> [X] CGI
- From the “osTicket-Installation-Files” folder, install PHP Manager for IIS (PHPManagerForIIS_V1.5.0.msi)
  
 ![Screenshot 2025-02-24 174353](https://github.com/user-attachments/assets/358cdc71-81ee-4084-860d-3ac5100ddfc9)


<h2>Installation Steps</h2>

![image](https://github.com/user-attachments/assets/818ffdfb-bba2-46c9-985b-58ce45dc5c54)


<p>
</p>
<p>
Create the directory C:\PHP

From the “osTicket-Installation-Files” folder, unzip PHP 7.3.8 (php-7.3.8-nts-Win32-VC15-x86.zip) into the “C:\PHP” folder
</p>
<br />

<p>

![image](https://github.com/user-attachments/assets/03e598dc-5193-4b10-a534-e946b3306082)


</p>
<p>
From the “osTicket-Installation-Files” folder, install MySQL 5.5.62 (mysql-5.5.62-win32.msi)
</p>
<br />

<p>

![image](https://github.com/user-attachments/assets/a209d6f1-92f8-4088-bcee-578aabbd9f59)


</p>
<p>
From the “osTicket-Installation-Files” folder, install HeidiSQL.
Open Heidi SQL
Create a new session, root/root
Connect to the session
Create a database called “osTicket”
Continue Setting up osTicket in the browser
MySQL Database: osTicket
MySQL Username: root
MySQL Password: root
Click “Install Now!”


</p>
<br />
