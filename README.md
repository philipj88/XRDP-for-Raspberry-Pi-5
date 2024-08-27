# XRDP-for-Raspberry-Pi-5
Guide on setting up remote access to a Raspberry Pi 5 without a monitor using XRDP.
This guide explains how to set up an SD card for a new Raspberry Pi then start the Raspberr Pi and find its IP address through the command line of the desktop to remote into it. The following steps explain how to do it from the start:
1) Download and install the Raspberry Pi imager from https://www.raspberrypi.com/software/
2) When you start the Raspberry Pi imager, you will see 3 options: Raspberry Pi Device, Operating System, and Storage.
3) Click on choose device and select the type of Raspberry Pi that you have.
4) Then click on Operating System to select the OS you want. Raspberry Pi OS is the most popular.
5) Then for storage select your SD card that should be in the desktop and will be placed in the Raspberry Pi after OS is ready.
6) Click next, then a screen will pop up saying "would you like to appy OS customization setting?" its important to click on edit settings as we have to configure internet network and password and also username and password. The reason its important to do this set is that we will never be able to connect to a Raspberry Pi that does not have a monitor without preconfiguring it prior to installing the OS.
7) Make sure you put the internet information of the same network that your desktop is using.
8) Make sure to remember your user name and password as you will need them when connecting after installation is complete.
9) Then click save then click on "Yes" on the "Would you like to apply OS customization settings?" screen.
10) It will warn you that all existing data on the SD card will be erased, click yes.
11) It will take around 10 minutes for the Raspberry Pi OS to install on the SD card. Notice that your internet information and your username and password have been preconfigured by now. It means once installation is complete and you put the SD card in the Raspberry Pi, it will connect to the internet.
12) Its important to note that by default SSH is not enabled. We will need to SSH into the Raspberry Pi to install XRDP. Hence, we have to enable the OS to allow SSH before we insert the SD card into the Raspberry Pi.
13) To enable SSH from the desktop side for the Raspberry Pi OS, we have to create a text file called SSH but without any extention in the main directory in the SD card.
14) 
