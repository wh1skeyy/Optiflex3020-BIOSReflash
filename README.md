# Optiflex3020-BIOSReflash
A Possible Fix For Soft Reboot Error on Dell Optiplex 3020s

## Prerequisites
DIH81R Motherboard - Used on Dell Optiplex 3020s and 3020 SFFs
CH314A USB Programmer
Solder Station (Optional)

## The Issue
On the particular Version A02 BIOS firmware of the Dell's DI81R Motherboard, there's a bug that makes the machine unable to perform soft reboot. This makes the PC goes black screen when restarting, and makes the BIOS upgrade process impossible (as the machine will have to restart to complete a BIOS upgrade)
The solution performed in this case would be to flash in BIOS ver A10 in the BIOS MCU using a CH314A programmer.
The chip in this case is the 8-pin MX25L6473E, located at the bottom of the RAM slots

## Disclaimer
