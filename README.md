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
<img src="https://i.imgur.com/jYyGik3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now we need to install Microsoft Visual C++ followed by a mySQL database where osTicket will store all of its data. remember to select typical setup and standard configuration during installation process. Set up your password and continue. 
</p>
<br />

<p>
<img src="https://i.imgur.com/UZ7fxNT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Select new after Heidi SQL is installed and it will ask you to set passwords. Also remember after installing PHP maanager or configuring anything always go back to IIS interface and refresh or quasi stop and start the webserver to enable that your configurations go through. 
</p>
<br />

<p>
<img src="https://i.imgur.com/WBxc9rk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next back in the osTicket installation folder find the upload folder and move its contents to the C: drive folder that you named PHP earlier and rename it to osTicket ( spell it exactly like this it is crucial). Put it in the following folder PHP > inetpub > wwwroot then paste in here before you rename. Refresh webserver in ISS once again!
</p>
<br />

<p>
<img src="https://i.imgur.com/IpNjjOR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next you will need to enable extensions in the PHP manager, so open IIS and click on PHP manager icon and in there click on enable/disable extensions. 
</p>
<br />

<p>
<img src="https://i.imgur.com/yR1eidm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Browse over to the right column in the PHP manager interface on IIs and click on browse to HTTP....
</p>
<br />

<p>
<img src="https://i.imgur.com/5fOaCAD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Then enable the following : php_imap, php_intl, php_opcache. Once you do this and go to osTicket installation folder, open up osTicket and you will see everything enabled except the last 2 applications ( thats ok you dont need these) Click continue and fill out all your information. Also at the bottom put the passwords in that you set during the HeidiSQL install and your database which should be osTicket and hit review and create. 
</p>
<br />

<p>
<img src="https://i.imgur.com/J7R8fRj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now once everything is approved you will be able to access osTicket through various URLs. 
</p>
<br />

<p>
<img src="https://i.imgur.com/lRkD7Zk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click on the top left URL that will take you to the localhost to the osTicket support Center and you now have osTicket installed on Windows 10. Enjoy!
</p>
<br />


























