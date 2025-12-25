4U12G BC-250 is a part of ASRock 4U12G BC-250 Mining Rig

based on broken PS5 APU, with 16GB GDDR6 ram (10+6)

current driver reddit (https://www.reddit.com/r/linux4noobs/comments/1bvdfi3/bc250_driver/)

modded mesa repo https://aur.archlinux.org/packages/amdonly-gaming-mesa-git

bios mod https://gitlab.com/TuxThePenguin0/bc250-bios/

Smokeless umaf, you can change RAM:VRAM ratio via UMA on BIOS v3.00+ chipset > gfx Config integrated graphics controller -> Forces UMA mode -> uma specified https://github.com/DavidS95/Smokeless_UMAF -- but there is no need to use it.

also to flash bios just use flashrom under any os, its installed by default mostly.

sudo flashrom -p internal -r backup.bin

sudo flashrom -p internal -w newbios.bin




Collection of BIOS ROMs for the BC-250

BC250_3.00.ROM -  Stock dump from a BC-250 running firmware P3.00 after a settings clear, may contain some data like EFI variables

BC250_3.00_CHIPSETMENU.ROM -  Modded firmware with the chipset menu exposed and modified to allow access to NBIO Common Options. Based on BC250_3.00.ROM



Warning

Nothing in this repository is supported or has any kind of warranty. This is a dump of my work, it meets my standards for functionality but isn't polished.

As always, before flashing anything TAKE BACKUPS.




_________________________________________

READ PDF FILE

REPLACE COMMAND WITH THIS FOR MODDED BIOS

AfuEfix64.efi BC250_3.00_CHIPSETMENU.ROM /p /b/ /n /k /x /ric:e




Download ZIP File From Here Or Github: https://github.com/MrrZed0/bc-250-bios

Video: https://youtu.be/1FuWU0PRUVU




#bc250 #bc-250 #asrockbc-250 #asrockbc250
