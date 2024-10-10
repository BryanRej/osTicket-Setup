<h1>osTicket Setup</h1>

<h2>Description</h2>
This project is an extension of the SOC Homelab project and uses a Windows 2022 Standard operating system. It is made to simulate a help desk environment through an admin view.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Powershell</b> 


<h2>Environments Used </h2>

- <b>Vultr Cloud, Windows 2022 Standard, </b> 

<h2>Project walk-through:</h2>
  
Setup Vultr: Booting up my Windows OS. Installing osTicket. <br/>
<img src="https://i.imgur.com/169UIFO.png" width="80%" alt="Setup"/>
<img src="https://i.imgur.com/TKRTOIb.png" height="80%" width="80%" alt="Setup"/>
<img src="https://i.imgur.com/AK6Xqs9.png" height="80%" width="80%" alt="Setup"/>
<img src="https://i.imgur.com/J50zDSe.png" height="80%" width="80%" alt="Setup"/>
<img src="https://i.imgur.com/5iNVKoB.png" height="80%" width="80%" alt="Setup"/>
<br />
<br />

<br />
  
Configuring custom firewall rules on my Windows device. <br/>
<img src="https://i.imgur.com/eDvBvvp.png" height="80%" width="80%" alt="Setup"/>
<img src="https://i.imgur.com/UT9G3QD.png" height="80%" width="80%" alt="Setup"/>
<br />

  
Installing Xampp Apache distribution for the osTicket backend database. I also tweak some of the configuration files to match the Ip address of my Windows machine.<br/>
<img src="https://i.imgur.com/CYlAO3r.png" height="80%" width="80%" alt="Setup"/>
<img src="https://i.imgur.com/nmaxOlM.png" height="80%" width="80%" alt="Setup"/>
<img src="https://i.imgur.com/w6bTGdl.png" height="80%" width="80%" alt="Setup"/>
<img src="https://i.imgur.com/yrMqNpo.png" height="80%" width="80%" alt="Setup"/>
<img src="https://i.imgur.com/XzLHS6k.png" height="80%" width="80%" alt="Setup"/>
<img src="https://i.imgur.com/HUal7jm.png" height="80%" width="80%" alt="Setup"/>
<br />

Loading into the Xampp control center. Creating the osTicket database and admin privileges.<br/>
<img src="https://i.imgur.com/WfS8IQy.png" height="80%" width="80%" alt="Setup"/>
<img src="https://i.imgur.com/UW4w9qa.png" height="80%" width="80%" alt="Setup"/>
<img src="https://i.imgur.com/4TQ9v7o.png" height="80%" width="80%" alt="Setup"/>
<img src="https://i.imgur.com/pVeiV68.png" height="80%" width="80%" alt="Setup"/>
<img src="https://i.imgur.com/EiFWcUe.png" height="80%" width="80%" alt="Setup"/>
<img src="https://i.imgur.com/6I2J0Co.png" height="80%" width="80%" alt="Setup"/>
<br />

Adding my osTicket server to my SOC virtual private cloud containing other devices. Only specified IPs will have access to the osTicket server.<br/>
<img src="https://i.imgur.com/V8G66r4.png" height="80%" width="80%" alt="Setup"/>
<br />

Visiting the osTicket web setup page. Setting up the environment.<br/>
<img src="https://i.imgur.com/gVWC9oT.png" height="80%" width="80%" alt="Setup"/>
<img src="https://i.imgur.com/7opNVC1.png" height="80%" width="80%" alt="Setup"/>
<br />

Adding the missing configuration file to complete the osTicket web installation. I need to open a Powershell environment to configure the proper file.<br/>
<img src="https://i.imgur.com/TUgEXU2.png" height="80%" width="80%" alt="Setup"/>
<img src="https://i.imgur.com/8bBtOr1.png" height="80%" width="80%" alt="Setup"/>
<img src="https://i.imgur.com/EwsKJTW.png" height="80%" width="80%" alt="Setup"/>
<img src="https://i.imgur.com/jMc2iCy.png" height="80%" width="80%" alt="Setup"/>
<br />

Loading into the Xampp control center. Creating the osTicket database and admin privileges.<br/>
<img src="" height="80%" width="80%" alt="Setup"/>
<img src="" height="80%" width="80%" alt="Setup"/>
<img src="" height="80%" width="80%" alt="Setup"/>
<img src="" height="80%" width="80%" alt="Setup"/>
<img src="" height="80%" width="80%" alt="Setup"/>
<img src="" height="80%" width="80%" alt="Setup"/>
<br />
