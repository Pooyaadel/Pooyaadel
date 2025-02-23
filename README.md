<h1> Active Directory Home Lab <h1/>
<h2>Description</h2>
Project consists of depolying two Virtual Machines through (Oracle Virtual Box) with one machine being the Domain Controller and the other machine being a Client.
<br />


<h2>Languages Used</h2>

- <b>PowerShell</b> 


<h2>Environments Used </h2>

- <b>VirtualBox</b>
- <b>Windows 10 ISO <b/>
- <b> Server 2019 ISO

<h2>Walk-Through:</h2>

<p align="center">
Configure Ipv4 for the Internal Network (Domain Controller): <br/>
<img src= "https://i.imgur.com/6ajFemH.png"/>
<br />

 
<br />
<br />
install Active Directory and Domain Services  <br/>
<img src="https://i.imgur.com/hOLXilS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create an Organizational Unit for Domain Admins using AD: <br/>
<img src="https://i.imgur.com/HwUz0U9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Install RAS(Remote Access Service)/NAT(Network Address Translation) to allow Windows 10 client  on virtual network to be able to access the DC network  <br/>
<img src="https://i.imgur.com/PQIogLH.png"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
