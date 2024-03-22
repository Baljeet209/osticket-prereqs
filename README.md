# osticket-prereqs
<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Install/Enable IIS
- Install Web Platform Installer 
- Install MySQL,setup username and password 
- Install C++ Redistributable 
- Configure permissions and install osTicket

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/b7rQD33.png"<
  /p>
<p>
Steps to Install and enable IIS 
Open control panel > Programs > Windows features > Internet information services > World wide web services > Application development features > Check CGI and check all of the common HTTP features > click ok and it will install IIS.Verify that IIS is up and running by going to the loopback address 127.0.0.1 it should look similiar to the picture 
</p>
<br />

<p>
<img src="https://imgur.com/BCMogcC
 /p>
<p>
Next Download and install PHP mananger for IIS,Rewrite module and PHP 7.3.8 and create a folder named PHP into the C:\ unzip the PHP 7.3.8 contents into the PHP folder, Download and install C++ Redistributable and then Download and install MySQL > Typical installation  > Launch config wizard > Standard Config > Set the root password to Password1 > Open IIS as admin > Register PHP > Restart IIS > Download and install osTicket > Extrat and copy upload folder to C:\inetpub\wwwroot > rename upload folder to osTicket > Reload IIS >Go to sites > Default > osTicket > on the right click Browse *.80 > 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
