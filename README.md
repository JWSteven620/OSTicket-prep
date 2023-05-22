<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/RNkpAvk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

- Open the following link in your VM
- Tutorial (https://docs.google.com/document/d/12QH7yrsaiUfYNOgZK7KgTSZQSJ-HYTSVcGFildWMRig/edit#)

<br />

<p>
<img src="https://i.imgur.com/Ye9LNTT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

- Right click start menu to access run then type control

<br />

<p>
<img src="https://i.imgur.com/QaiAeMS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<b>- Access Programs the select Turn windows features on or off than check and expand the following:</b>
  - Select Internet Information Services
  - World Wide Web Services
  - Application Development Features 
  - CGI
- Then select ok

<br />

<p>
<img src="https://i.imgur.com/NKK5kHJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

- This should popup if you attempt to access the local host (127.0.0.1) through the browser

<br />

<p>
<img src="https://i.imgur.com/89OYpgB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<b>- Begin downloading the following files:</b> 
   - PHP Manager
   - Rewrite Module
   - PHP 7.3.8
   - VC_redist.x86.exe 
   - MySQL 5.5.62
   - HeidiSQL

<br />

<p>
<img src="https://i.imgur.com/w1zkWC7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

- Select Download anyway

<br />

<p>
<img src="https://i.imgur.com/0MdXPhN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

- Type IIS in the search bar to access Internet Information Services 

<br />

<p>
<img src="https://i.imgur.com/XsBReVu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Navagate to osticket file and click browse *:80
</p>
<br />

<p>
<img src="https://i.imgur.com/bQlMHTL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<p>
<img src="https://i.imgur.com/xgSaxpw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Create a login for OSTicket
</p>
<br />

<img src="https://i.imgur.com/FBgbFog.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Login in Successful
</p>
<br />
