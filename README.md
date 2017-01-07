# PXE server install for automate linux distro installation
The PXE server is installed and setup on on Debian 8 64bit

#Requirements 

##DHCP Server
You can install dchp server on your debian or you can also use your router. You cannot use both.

##TFTP server

##Download ISO for distro


#Server configuration

- Put files in tftp server folder
- Make menu.cfg
- Install client

##Pro tips

- Make sure to change the boot order so when the computer reboots it won't reinstall the distro again automatically. Boot what was just installed instead. (example: Give a higher boot priority to the HDD and put the network boot last)

- If there are not enough monitors for connect every computer, put them in line and launch the installation in order (for example: from the left to the right) so computers will mostly finish in the same order. This is the most optimized way to do it and will avoid the need to try to figure which one is done by reconnecting the monitor to each of them one after another (that's a waste of time).
