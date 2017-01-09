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
=======
- Make sure to change the boot order so the computer won't reinstall the distro again automatically at reboot. Boot what was just installed, change the boot priority in the BIOS. (example: Give a higher boot priority to the HDD and put the network boot last)
- If there are not enough monitors for connect every computer, put them in line and launch the installation in order (for example: from the left to the right) so computers will mostly finish in the same order. This is rather effective when every computer has the same hardware. It's the most optimized way to do it and will avoid the need to try to figure which one is done by reconnecting the monitor to each of them one after another (that's a waste of time).

## Configuration hints

- The URL of the preseed configuration file can be changed in `/boot-screens/menu.cfg`
- The timeout length can be changed in `/boot-screens/syslinux.cfg`

## Screens

![2017-01-06-181250_3840x1080_scrot](https://cloud.githubusercontent.com/assets/6194072/21755778/a75b0f1c-d5e6-11e6-8058-8399265a38f6.png)
![2017-01-06-180756_3840x1080_scrot](https://cloud.githubusercontent.com/assets/6194072/21755779/a84669f8-d5e6-11e6-871b-c95c3cbeefe7.png)