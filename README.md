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

- Item 1 - Download osTicket zipfile and extract
- Item 2 - Install PHP Manager
- Item 3 - Install Microsoft Visual C++
- Item 4 - Configure PHP
- Item 5 - Install osTicket
- Item 6 - enable extensions
- Item 7 - Disable Inherited permissions/add new permissions
- Item 8 - Install HeidiSQL and create backend database
- Item 9 - Finish osTicket install/log in

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/zsHHCxM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download osTicket zipfile from trusted source on the web, extract these files into your desktop folder. 
</p>
<br />

<p>
<img src="https://i.imgur.com/CpPfVdG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>


</p>
<br />


<p>
<img src="https://i.imgur.com/9tlt8sG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />

<p>
<img src="https://i.imgur.com/UizeVNo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here is what the extracted folders should look like. Then extract!
</p>
<br />



<p>
<img src="https://i.imgur.com/vw0ebw1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Enable CGI in IIS ( Internet Information Services) by doing the following : Start menu > Control Panel > Programs. Click on "Turn Windows features on/off" In the box do as follows > expand World Wide Web Services > expand Application Development Features > check box for CGI. Acknowledge OK and wait for Install.
</p>
<br />

<p>
<img src="https://i.imgur.com/zSnQ8OQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Follow instructions above in this box. 
</p>
<br />

<p>
<img src="https://i.imgur.com/SfJt1mi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to your browser and input 127.0.0.1 to check IIS, if what the image shows is on your screen then you are good to go and move on.
</p>
<br />

<p>
<img src="https://i.imgur.com/ONfz3pU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now we need to unzip the actual osTicket files in the desktop and because osTicket runs on PHP we need to install PHP manager, rewrite module and create a directory in the C drive named PHP.
</p>
<br />

<p>
<img src="https://i.imgur.com/gAAdMAf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the osTicket installation folder there will be PHP binaries and these need to be extracted to a folder that you need to create in your C: drive. 
</p>
<br />

<p>
<img src="https://i.imgur.com/PiUUYd3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />

<p>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />

<p>
<img src="https://i.imgur.com/PiUUYd3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />

<p>
<img src="https://i.imgur.com/PiUUYd3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />

<p>
<img src="https://i.imgur.com/PiUUYd3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />


































