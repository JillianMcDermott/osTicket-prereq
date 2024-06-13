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
Google Drive of files used: https://drive.google.com/drive/u/1/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6

- Create a Virtual Machine in Microsoft Azure to conduct the installation
- Enable IIS, World Wide Web Services. and CGI through Windows Control Panel
- Install the files needed (see step link above as well as second steps for individual links)
- Item 4
- Item 5

<h2>Installation Steps</h2>

<p>
<img src="https://github.com/JillianMcDermott/osTicket-prereq/assets/172544849/fc956cfd-a74f-466f-8118-34c7a9a337f2"/>
</p>
<p>
The first step in this process after creating a virtual machine in Microsoft azure is enabling the Internet Infomation Services from the control panel of your virtual windows machine, this will be referred too as IIS for the rest of the tutorial. Ensure to expand the IIS and enable the World Wide Web Services, expand the World Wide Web Services, then expand the Application Developement Features and turn on CGI as well. 
</p>
<br />

<p>
  <img src="https://github.com/JillianMcDermott/osTicket-prereq/assets/172544849/6ddc2ac5-aaa2-42b1-8e30-ca9f1c4c5099"/>
<img src="https://github.com/JillianMcDermott/osTicket-prereq/assets/172544849/60351e06-58ea-4fa8-a9ad-70733e334698"/>
</p>
<p>
Next we have some files to download, but before we do that we need to make a new folder in the C drive of your machine labeled "PHP". This is where you will house the unzipped files from the first PHP file download.
  
Files to download

PHP zipped (this one gets moved to the C drive folder and unzipped from there): https://drive.google.com/file/d/1snNMtLdCOpMtkCyD4mvl9yOOmvVIp9fP/view?usp=drive_link

The rest of the links simply need to be installed normally, the mysql will ask for you to make a password.
  
PHP unzipped: https://drive.google.com/drive/folders/1yOk5ejp5Oe21USJfCgelyvdlJMwHRhxC?usp=drive_link

Rewrite: https://drive.google.com/file/d/1tIK9GZBKj1JyUP87eewxgdNqn9pZmVmY/view?usp=drive_link

MySQL: https://drive.google.com/file/d/1_OWh9p7VQLcrB0q_V7qT8yHl0xo5gv7z/view?usp=drive_link

VC_redist: https://drive.google.com/file/d/1s1OsGF3-ioO0_9LYizPRiVuIkb3lFJgH/view?usp=drive_link
<br />

<p>
<img src="https://github.com/JillianMcDermott/osTicket-prereq/assets/172544849/18ec3d2c-e8bb-4a55-9b10-b56af0ed5e86"/>
<img src="https://github.com/JillianMcDermott/osTicket-prereq/assets/172544849/e569d870-2ad7-4892-89c5-c16d6e5e3db4"/>
<img src="https://github.com/JillianMcDermott/osTicket-prereq/assets/172544849/c8513dda-da93-413c-97cf-f6d79d9cea1e"/>
<img src="https://github.com/JillianMcDermott/osTicket-prereq/assets/172544849/b07375b9-2a2f-45e2-b0d2-9ef023615e26"/>
</p>
<p>
Next we will run IIS as an administrator, simply right click thew application before launch and select "Run as Administrator".
Go to PHP Manager, and it shoudl show nothing, as seen in the above pic you will Register new PHP version and run the file you unzipped in the PHP folder from your C Drive. Register as prompted, once it's registered you can go back to the main page of IIS and restart IIS as pictured.
<br />
<p>
<img src="https://github.com/JillianMcDermott/osTicket-prereq/assets/172544849/91f9aa78-c0e8-4158-bcf8-915c45c95d89"/>
<img src=""/>
</p>
<p>
Now we are ready to install osTicket, once it is installed we will need to unzip the file, there are 2 files in the folder and the upload file must go to the "wwwroot" folder inside the "inetpub" folder in your C Drive. This may take a mintute to load. Once the "upload" file is unzipped in the wwwroot folder, rename it to osTicket.

osTicket Download: https://drive.google.com/file/d/1VeVXKlzHDRjeaVUL99ptq7qYbrbXdFxJ/view?usp=drive_link
<br />

</p>
<br />
