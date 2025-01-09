# installing-Metasploitable-in-VirtualBox


Let’s first discuss what Metasploitable is, it is a testing environment that is very useful for beginner who wants to practice and test their penetration testing skills and security research. It is a target machine that is used to discover and penetrate vulnerabilities so that the user gets an idea of real-life targets and machines.

In other words, Metasploitable is a virtual machine intentionally vulnerable version of Ubuntu designed for testing security tools and demonstrating common vulnerabilities.

To install this virtual machine in your virtual box, We assume that you have a virtual box installed on your system.

Installation
Step 1:<em><a href="https://sourceforge.net/projects/metasploitable/files/latest/download">"Download"</a></em> the Metasploitable file. 

<img src="Folder/image1.jpg">
 

Step 2: The file initially will be in zip format so we need to extract it, after extracting the file open VirtualBox.


<img src="Folder/step 2.jpg">
 

Step 3: Now as shown in the above image click on the <strong>New</strong> option in the Virtual box.

<img src="Folder/step 3.jpg">
 

now a window will pop up and you will be asked to provide some details like the name of your machine, installation path, type, and version.
fill in the details like:
Name: as per your choice
Path: leave as recommended
Type: Linux
Version: other (64-bit)

 <img src="Folder/step 4.jpg">

Step 4: Select the RAM you want to provide to the virtual machine. recommended (512Mb).

<img src="Folder/step 5.jpg">
 

Step 5: Now choose the option to use an existing virtual hard disk file.


 

Now locate the file that we have extracted.
Step 6: Now save the file and you will see that the instance is created with the name you have given.


 

We are good to go with the machine just press the start button from the top and wait for it to start and load the instance.

 

Step 7. once the instance is loaded you will be asked to provide a login name and password. By default the credentials are :


Default login: msfadmin
Default password: msfadmin

 

once you log in with credentials you will be directed to the machine and we are done with the installation process.
