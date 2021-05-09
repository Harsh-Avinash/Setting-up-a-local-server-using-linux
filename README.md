# Making-a-local-server-using-linux
So I had an old 2016 Dell latitute E6420 which I wanted to repurpose for something cool, I set up ubuntu server with ssh.

There are few simple steps:

1. Choosing an Operating System 
2. Downloading Ubuntu Server 20.04 and making a live bootable USB 
3. Booting into the USB and setting up the Server.

  Welcome Screen, 
  Keyboard Configuration, 
  Network Connections, 
  Configure Proxy, 
  Guided Storage Configurations, 
  Storage Configuration, 
  Profile Setup, 
  SSH setup, 
  Featured Server Snaps, 
  Installing System. 
  
4. Connecting Your server via Wi-Fi. 
Assuming you still have your ethernet wire plugged in, Install the following packages
rfkill , wireless-tools , net-tools and wpasupplicant
and view the private ip address.
Now from another computer 

If you are using windows download Putty or if you are Linux or MacOS user run the command 
ssh username@ip_addr
Enter your password
Voila! You have just accessed your system inside your private network.

5. Installing Webmin 

Webmin is a web-based interface for sysadmins. Using any modern web browser, you can setup user accounts, Apache, file sharing and much more. Webmin removes the need to manually edit Unix configuration files like /etc/passwd, and lets you manage a system from the console or remotely.
Follow this guide to install webmin.


https://dev.to/jayesh_w/this-is-how-i-turned-my-old-laptop-into-a-server-1elf
https://ubuntu.com/download/server
https://rufus.ie/en_US/
https://www.linuxbabe.com/command-line/ubuntu-server-16-04-wifi-wpa-supplicant
https://linuxize.com/post/how-to-install-webmin-on-ubuntu-18-04/
