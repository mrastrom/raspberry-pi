# Raspbian Light
## Preconditions  
* Empty SD memory
* Computer (OS: Ubuntu)
* Raspberry Pi with no display, keyboard or mouse.

## Get Image
Download [Raspberry Pi Imager](https://www.raspberrypi.org/downloads/)
Install/Download "Raspbian light" image to SD

Mount sd card:   
`sudo mount /dev/sdb1 /mnt`

### Enable SSH
Add file "ssh" in root on the mounted SD card it kan be empty

### Enable and config WIFI
Add and alter it to your needs [wpa_supplicant.conf](https://github.com/mrastrom/raspberry-pi/blob/master/wpa_supplicant.conf) file to root on mounted SD card
UMount sd card:  
`sudo umount /mnt`

