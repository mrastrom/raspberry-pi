# Raspbian Light

## Install and configurate without display and keyboard or mouse
### Preconditions  
* Empty SD memory
* Computer (OS: Ubuntu)
* Raspberry Pi with no display, keyboard or mouse.

Download [Raspberry Pi Imager](https://www.raspberrypi.org/downloads/)
Install/Download "Raspbian light" image to SD

Mount sd card:   
`sudo mount /dev/sdb1 /mnt`

### Enable SSH
Add file named "ssh" in root on the mounted SD card it kan be empty, to start ssh deamon on startup.

### Enable and config WIFI
Add and alter it to your needs [wpa_supplicant.conf](https://github.com/mrastrom/raspberry-pi/blob/master/wpa_supplicant.conf) file to root on mounted SD card
UMount sd card:  
`sudo umount /mnt`
### Run Raspberry Pi
Insert the SD card into the Raspberry Pi and boot.
Find the RPi (Raspberry Pi) IP address and use it to connect to the RPi from your computer using SSH or try using the default name 'raspberrypi'.
Ex.    
`sudo ssh pi@<an ip address>`    
or  
`sudo ssh pi@raspberrypi`  
or  
`sudo ssh pi@raspberrypi.local`  
depending on your local router...  
To discover ip numbers on your LAN use ex. [IP Address Tracker](https://www.solarwinds.com/free-tools/ip-address-tracker?CMP=ORG-BLG-DNS)

User/password = pi/raspberrypi **REMEBER:** Change default password.
#### Config
##### Quick and easy
This is the easiest way to quickly configure the computer. Use:    
`sudo raspi-config`  
