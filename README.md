# EFI-Hackintosh-for-Ryzen-5800-and-R9-270x
My EFI for Monterey


![This is an image](https://i.imgur.com/y2sxYGm.png)
As you can see I'm running this Mac OS Monterey without any problem.
My advice it's to try it... At the beggining I was downloaded on EFI for 3200G and replace some text, but the sistem was working as it should on that EFI.
All you need to do it's to TRY it.

This EFI it's been made by me, and it's bassed on my configuration:


 - Motherboard: Aorus B450 Elite
 - CPU: Ryzen 5800x
 - GPU: R9 270x (it was the only GPU I've found in the house :) ) - ALSO it's working with RX 560 aswell.
 - SSD Samsung 970 EVO 1T
 - SSD Kingston 250 GB (here it's sleeping the Monterey)
 - 24GB Ram

All you need to do is:

- Download the Monterey from here: https://www.mediafire.com/file/u8drur0yzb18ap5/Olarila_Monterey_12.4.raw/file , write it on USB with BalenaEtcher 
- Second step it's to burn the raw image on an USB stick (minim 16GB)
- Put the EFI file to another USB stick (minim 4GB Required)
- Boot from the second USB stick (where it';s the file) and select Install Mac OS (external)
- Install the OS
- After the OS it's finished BOOT from EFI stick, and open the Monterey USB stick. Click on ESP Mounter PRO
- Mount EFI and copy your EFI folder from the second stick to HDD/SSD
- Reboot and boot now from HDD/SSD and that's it :)

Have fun
Reboot and that's it :)
