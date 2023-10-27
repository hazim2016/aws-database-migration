<p align="center">
<img src="https://imgur.com/t5VLlQW" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />



- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> 
<h2>List of Prerequisites</h2>

- AWS account with root privilige
- Kubernetes
- Linux
- EC2 instance


<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/mIEtH1v.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install Web Platform Installer. Open the installation Add MySQL 5.5. Then add all PHP version x86 up untill 7.3.
</p>
<br />

<p>
<img src="https://i.imgur.com/2i7NQJ3.png"80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Fix failures by installing C++ and PHP manager for the program to run.
</p>
<br />

<p>
<img src="https://i.imgur.com/muyQAU2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download and extract the osTicket folder. Now the folder is visbible in downloads in the file explorer. 
</p>
<br />

<p>
<img src="https://i.imgur.com/F2gUHTh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Copy the osTicket and paste the osTicket folder in the wwwroot folder
</p>
<br />

<p>
<img src="https://i.imgur.com/7HrXXWk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click on site file and open osTicket. Then Open Port 80 on the browse folder which is the http port. osTicket installer should appear after selecting port 80.
</p>
<br />

<p>
<img src="https://i.imgur.com/nTiyhlo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />

<p>
<img src="https://i.imgur.com/arJpoJO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Enable PHP_imap.dll, PHP_intl.dll, PHP_opcache.dll
</p>
<br />

<p>
<img src="https://i.imgur.com/B4R53Kc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Rename ost-sampleconfig.php to ost-config.php. Change permission setting from disabled inherentence and give all permission to everyone so osTicket can make changes to the file. In anycase dealing with permissions and access you have to give the least permission. This is just for the purpose of the lab.
</p>
<br />

<p>
<img src="https://i.imgur.com/62L9IQk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click continue on the osTicket page the and you can fill out the basic installation with your information.
</p>
<br />
                                                                                                 
<p>
<img src="https://i.imgur.com/jLwi9EJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download and install HeidiSQL
</p>
<br />

<p>
<img src="https://i.imgur.com/LjB1Lxu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Sign into HeidiSQL with your credentials and Create a database called osTicket.
</p>
<br />

<p>
<img src="https://imgur.com/jGYWCUj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
You should recieve the Congratulation page.
</p>
<br />
                                                                                                 
