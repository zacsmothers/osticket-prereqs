<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>OsTicket - Installation NOT COMPLETE</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b>

<h2>Installation Steps</h2>

- Step 1 - Enable IIS in Windows VM with CGI and common HTTP features
- Step 2 - Configure IIS in Windows VM
- Step 3 - Install and enable software for OsTicket
- Step 4 - Install SQL database sotware to enable OsTicket

<h2>Picture and Description</h2>

<p>
<h3>Enable IIS in Windows VM with CGI and common HTTP features</h3>
<img src="https://i.imgur.com/1DAOqDZ.png" height="80%" width="80%" alt="Enable IIS Steps"/>
</p>
<p>
To install the ticketing system first the IIS (internet information services) must be enables from within Windows features, then under IIS the CGI (Common Gateway Interface) and common HTTP features must be enabled. CGI is a standard protocol used to enable web servers, such as IIS, to execute external programs, scripts, and generate dynamic content for web pages. The common HTTP features help manage web traffic, enhance security, and improve the functionality of a web server.
</p>
<br />

<p>
<h3>Configure IIS in Windows VM</h3>
<img src="https://i.imgur.com/PSk8Jlt.png" height="80%" width="80%" alt="Configure IIS Steps"/>
</p>
<p>
Then after downloading the required software IIS needs to be configured to install and launch the ticketing software, one of the software packages required was PHP manager, after downloading, it must be registered within IIS by providing a path to the executable "php-cgi.exe."
</p>
<br />

<p>
<h3>Install and enable software for OsTicket</h3>
<img src="https://i.imgur.com/bixFBKY.png" height="80%" width="80%" alt="Install and enable software for OsTicket"/>
</p>
<p>
The next step is to download OsTicket itself, after the installation is complete certain features are recommended to enable so that all the features of the software can be utilized. This is done within PHP Manager in the "enable or disable an extension" settings.
</p>
<br />

<p>
<h3>Install SQL database sotware to enable OsTicket</h3>
<img src="https://i.imgur.com/lGZhOoM.png" height="80%" width="80%" alt="Install SQL database sotware to enable OsTicket"/>
</p>
<p>
The next step is to install and connect Heidi SQL which is used to make it easier to interact with the MySQL server, which was another required software used to create the ticketing system.
</p>
<br />
