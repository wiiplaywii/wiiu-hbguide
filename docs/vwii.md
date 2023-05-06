# Virtual Wii Modding

?> You will need a FAT32 SD Card for this. If you already used one to mod your WiiU, you can still use that.

# Needed Files

[Tiramisu CFW](https://tiramisu.foryour.cafe/)

[vWii Compat Installer](https://github.com/TheLordScruffy/vwii-compat-installer/releases)

[d2x cIOS installer](https://hbb1.oscwii.org/hbb/d2x-cios-installer/d2x-cios-installer.zip)

[Patched IOS80 Installer](https://hbb1.oscwii.org/hbb/Patched_IOS80_Installer_for_vWii/Patched_IOS80_Installer_for_vWii.zip)

# SD Preperation

1. Insert the SD into your Computer.
2. Copy over the apps folder from the IOS80 Installer (after extracting)
3. Copy over the d2x-cios-installer folder from d2x_cIOS_Installer.zip
4. If not already modded, copy over the contents from Tiramisu.zip to the SD.
5. Copy over the compat_installer.elf file to your wiiu/apps folder.
6. Eject the SD out of your PC and put it in your WiiU.

# NAND Dumping

1. On the Wii U's browser, navigate to wiiuexploit.xyz

3. Click run exploit on the gamepad.

3. Hold B down on the gamepad to enter the NAND Dumper.

6. Use the d-pad on the Gamepad to choose these dump settings:

Dump SLC: yes

Dump SLCCMPT: yes

Dump MLC: no

Dump OTP: yes

Dump SEEPROM: yes

5. Press A on the Gamepad to dump.

6. After the dumping has ended, power down the Wii U, Eject the SD from your Wii U, and put it in your computer.

7. NAND Backup, move the slccmpt.bin, otp.bin, seeprom.bin, slc.bin, Files to your computer in a safe folder.
