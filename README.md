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
Before installing osTicket, ensure you have the following components installed and configured:

1, Windows Server 2019 or Windows 10 (for testing)
2, Internet Information Services (IIS) with CGI enabled
3, PHP 7.4 or later (Ensure necessary extensions are enabled)
4, MySQL Server 5.7 or later (For database management)
5, osTicket Download Package (Latest version from the official site)
6, SMTP/IMAP Email Settings (For ticket automation and notifications)
7, Microsoft Web Platform Installer (Optional: for ease of installation)

<h2>Installation Steps</h2>

- Follow these steps to install osTicket:

- <h2>Step 1: Install IIS and Required Components</h2>
1, Open Server Manager → Select Add roles and features.
2, Choose Role-based or feature-based installation.
3, Under Server Roles, select Web Server (IIS) and CGI.
4, Click Next and install the required features.

- Download and install PHP 7.4+ from the official website.
- Enable required extensions such as:
    * php_imap.dll
    * php_mysql.dll
    * php_gd2.dll
    * php_curl.dll
 - Add the PHP directory to system environment variables.

<h2>Step 3: Install MySQL</h2>

1, Download MySQL Server 5.7+ and install it.
2, Set up a root user and password.
3, Create a database for osTicket:


<h2>Step 4: Download and Configure osTicket</h2>
1, Download the latest osTicket package from osTicket.com.
2, Extract the files into C:\inetpub\wwwroot\osticket.
3, Rename ost-config-sample.php to ost-config.php.




<h2>Step 5: Configure IIS for osTicket</h2>
1, Open IIS Manager.
2, Add a new site pointing to C:\inetpub\wwwroot\osticket.
-3,Set the application pool to No Managed Code and enable FastCGI.



<h2>Step 6: Install osTicket via Web Installer</h2>
1, Open a browser and navigate to http://localhost/osticket/setup.
2, Follow the installation wizard and enter database credentials.
-3,Complete the installation and remove setup directory for security.


<h2>Step 7: Configure Email Settings</h2>
1, Go to Admin Panel → Emails → Settings.
2, Configure SMTP and IMAP settings for ticket automation.




<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
