<p align="center">
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

- Azure Virtual Machine
- Install osTicket files
- Install PHP Mnager
- Install HeidiSQL

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/oTihL1x.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In Microsoft Azure search "Resource Group" click on it and click create.
</p>
<br />

<p>
<img src="https://i.imgur.com/pOSnast.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a resource group and name it "os-Ticket". Then click "Review & Create" Then when the "validation passes" click "Create".
</p>
<br />

<p>
<img src="https://i.imgur.com/LeYGT0k.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1) Click on your VM you named (os-ticket). 2) Make sure the resource group is the same name that you created in the resource group part. 3) Open up remote desktop in your windows machine from the search bar of your computer. 4) then you want to go to your Virtual Machine & find your VM's public IP Address & copy it. 5) Paste the IP address you just copied, to your remote desktop & hit connect. After it connect successfully connect hit "yes".
</p>
<br />

<p>
<img src="https://i.imgur.com/e8YhMId.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click on use a different account and log in using the account & pw you used on the "os-ticket" VM. After it connect successfully connect hit "yes". You should have a seperate window pop up loading a windows browser.
</p>
<br />

<p>
<img src="https://i.imgur.com/vvcRCjy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
On your computer (Not the VM) go to the control panel. You can do this by searching control panel in your windows. Click on programs. After that you should see option under programs & features. Select the one with the shield that say "Turn windows features on or off". Here you will find the feature thats in the photo above. 1) find "Internet Information Service" & click it so it drops down. 2) Find "World Wide Web" under the "Internet Information Services" drop down menu & select that to drop down more options. 3) Find CGI under "World Wide Web" and check it to turn the CGI on. Then click "OK". After this you'll need to download the neccessary files for the next steps. Here's a link: https://drive.google.com/drive/u/1/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6
</p>
<br />

<p>
<img src="https://i.imgur.com/vvcRCjy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1.) You want to download the [PHP Mananger For IIS] & run the installation. Nothing special needs to be added. Just next everything & install. 2.) Download & install the [Rewrite Module]. This one is also straight forward & nothing extra needed to install. Just next and Finish. 4.) Next you need to create PHP in your "C: Drive" just like in the image above. Load your file explorer and click on C: Drive. Then right click, click new then folder & name it PHP. 
</p>
<br />

<p>
<img src="https://i.imgur.com/Pgdl9dS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next were going to download the PHP 7.3.8 file & move all files to the PHP file we created in file explorer (Like in the image above). 
</p>
<br />

<p>
<img src="https://i.imgur.com/c3B7zum.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download My SQL and run the install & at the end make sure the [lauch] is checked so its launched when done installing.It launch another intall and you want to click nect until then Click on [Standard Configuration]. Once you get to the point where you create a  password. Use Password1 for the password [or create your own]. You want to write this on your note pad to remember. hit next and exucute. should look like photo when done.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
