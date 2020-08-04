Getting Started

Step 1: Connect to the server using ssh client putty. How To Connect Ubuntu Server Using Putty

Step 2: Make sure that RDP port is enabled on the Ubuntu instance in which you are going to install lxde. Update the server and install lxde using the following commands.

sudo apt-get update -y   
sudo apt-get install lxde -y

Step 3:  Install xrdp to establish a remote desktop connection since you can’t have a GUI using putty. Use the following command to install xrdp

sudo apt-get install xrdp -y
 
Step 4: Set a password for the default user “ubuntu”, as remote desktop connection requires username and password.

sudo passwd ubuntu

Note: You can set up your own user and password for remote desktop

Step 5: Start the windows remote desktop client and enter the public DNS or the public IP of your server instance and hit connect.


Step 6: Enter the username and password of the server instance that we created in step 5 and hit ok. Make sure RDP 3389 is enabled in your security group.

Note: If you are looking for more Linux command line hands on, use pluralsight 10 days free account to learn Linux Command Line

Bingo!! you can start using your Ubuntu server with GUI via the remote desktop connection.

Lightweight GUI for Linux on ec2
