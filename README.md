<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Enable IIS in Windows With CGI
- Download and Install PHP Manager for IIS
- Download and Install Rewrite Module
- Create directory C:\PHP
- Download and unzip PHP into PHP folder on C:\PHP
- Install C++
- Install MySQL
- Open IIS as an Admin
- Register PHP

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/KUl0h24.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
</p>
<p>
Navigate to Control Panel, click Programs, click "Turn Windows Features On or Off" and then scroll to Internet Information Services and mark the checkbox. Click the IIS tab, then click the World Wide Web Services, click the Application Development Features. Lastly mark the CGI box to enable the feature.  
</p>
<br />

<p>
<img src="https://i.imgur.com/o2tajU3.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The next step in the osTicket installation, is downloading the PHP Manager. Simply download the file, and open the file once downloaded, and continue the installation process until complete. 
</p>
<br />

<p>
<img src="https://i.imgur.com/JhvNq4x.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once the PHP Manager is done downloading, the Rewrite Module must be installed. Simply click download and follow the installation instructions. 
</p>
<br />

<p>
<img src="https://i.imgur.com/h1hkb9l.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now a PHP folder must be created in the C directory to unzip PHP into.   
</p>
<br />

<p>
<img src="https://i.imgur.com/brzGGO5.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Unzip the PHP files into the PHP folder on the C directory.  
</p>
<br />

<p>
<img src="https://i.imgur.com/keEPadv.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download Microsoft Visual C++, and then follow installation instructions. 
</p>
<br />

<p>
<img src="https://i.imgur.com/4PXcE7X.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download MySQL and install. After installation, launch configuration wizard, click the standard configuration option and choose a Password. 
</p>
<br />

<p>
<img src="https://i.imgur.com/q8ClDET.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Open Internet Information Services as an Admin and doubleclick PHP Manager. 
</p>
<br />

<p>
<img src="https://i.imgur.com/Fu13HfZ.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click Register New PHP Manager, click the path to the C directory, click the PHP folder, and then finally click the php-cgi executable. The prerequisites to the osTicketing system are now installed.  
</p>
<br />
