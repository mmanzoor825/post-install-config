<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-installantion</h1>
Setting up and configuring osTicket .<br />

<h2>Steps</h2>

<p>
<img width="500" height="350" alt="image" src="https://github.com/mmanzoor825/post-install-config/assets/138532574/3b2e3892-0915-4ba9-91af-dcbbe96558b4">
<P>
  First, rename the ost-sampleconfig.php file in C:\inetpub\wwwroot\osTicket\include\ost-sampleconfig.php to "ost-config.php". Change the permissions of the file to allow all access to everyone. Continue setup in the webpage.
</P>

Download and install:
- [HeidiSQL](https://docs.google.com/document/d/1WovrX2DaS9xkfaSr4LXyB4YnnWpXIgPCMMbbfgHmGVw/edit)
- Open the application > create a new session, root/enter password from mySQL > Connect to the session > Create a new database called "osTicket". Finish setting up osTicket webpage installation. Clean up by deleting C:\inetpub\wwwroot\osTicket\setup and by changing ost-config.php file permissions to read only.

<p>
<img width="681" alt="image" src="https://github.com/mmanzoor825/post-install-config/assets/138532574/30859163-050e-473a-9d3e-4de95974f0f0">
<P>
  Go to the local help desk login page (http://localhost/osTicket/scp/login.php) and use login information created during osTicket setup.  
</p>
<br />
