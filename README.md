# 2nd-Semester-Project
The tasks are as follows;
LAUNCHING EC2 INSTANCE
logged onto my AWS account from google chrome browser
click on services, select compute service, click on ec2 option 
click on launch instance
Type in my server name as "2nd Semester" 
Selected Ubuntu as my AMI
Created a new key pair while namimg it "2nd-Semester"
launch instance at the bottom right corner button

Install Linux distribution Using Windows Features
Step 1:Open the Start menu and type "Windows features" into the search bar and click on "Turn Windows Features On or Off".
Step 2:Tick the "Windows Subsystem for Linux" checkbox and press the “OK” button.
Step 3:When the operation is complete, you will be asked to restart your computer.
After that, use the Microsoft Store app and look for the Linux distribution you want to use.
Install the Linux distro of your choice.
Step 4:The Linux distribution can be launched from the Start menu.


INSTALLING AND CONFIGURING APACHE WEB SERVER
launch Ubuntu CLI 
SSH into cd /mnt/c/Users/PC/Downloads
check apache status with sudo systemctl status apache2
from my terminal, i download apache with the command "sudo apt install apache2"
enter my sudo password and wait for few seconds
type "y" when prompted for installation confirmation and wait till installation is completed
run the command "sudo apt upgrade" 
then run " sudo apt dist-upgrade" to ensure all necessary plug-ins are installed
check apache status on system with "sudo systemctl status apache2" and confirm apache is actively running
use the command "cd /var/" the "ls" to confirm presence of "www" webpage on my apache
Features
After loading Apache2 default page
run "sudo apt search libapache2-mod" 
sudo ufw allow 80,443/tcp....... to configure port to 80
sudo ufw status...... to check apache firewall status and it says inactive
sudo ufw enable.... to activate apache firewall 
