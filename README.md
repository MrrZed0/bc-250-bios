# Asrock BC-250 Modded BIOS
4U12G BC-250 is a part of ASRock 4U12G BC-250 Mining Rig

based on broken PS5 APU, with 16GB GDDR6 ram (10+6)

current driver reddit (https://www.reddit.com/r/linux4noobs/comments/1bvdfi3/bc250_driver/)

modded mesa repo https://aur.archlinux.org/packages/amdonly-gaming-mesa-git

bios mod https://gitlab.com/TuxThePenguin0/bc250-bios/

Smokeless umaf, you can change RAM:VRAM ratio via UMA on BIOS v3.00+ chipset > gfx Config integrated graphics controller -> Forces UMA mode -> uma specified https://github.com/DavidS95/Smokeless_UMAF — but there is no need to use it.

also to flash bios just use flashrom under any os, its installed by default mostly.

sudo flashrom -p internal -r backup.bin

sudo flashrom -p internal -w newbios.bin

______________________________________________________

READ PDF FILE

REPLACE COMMAND WITH THIS FOR MODDED BIOS

AfuEfix64.efi BC250_3.00_CHIPSETMENU.ROM /p /b/ /n /k /x /ric:e

 

# Video: https://youtu.be/1FuWU0PRUVU

#bc250 #bc-250 #asrockbc-250 #asrockbc250
