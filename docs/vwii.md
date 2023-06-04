# Virtual Wii Modding

?> You will need a FAT32 SD Card for this. If you already used one to mod your WiiU, you can still use that.

# Needed Files

- [Tiramisu CFW](https://tiramisu.foryour.cafe/)

- [vWii Compat Installer](https://github.com/TheLordScruffy/vwii-compat-installer/releases)

- [d2x cIOS installer](https://github.com/davebaol/d2x-cios/releases/download/d2x-v11-beta1/d2x-v11-beta1-vWii.7z)

- [Patched IOS80 Installer](https://hbb1.oscwii.org/hbb/Patched_IOS80_Installer_for_vWii/Patched_IOS80_Installer_for_vWii.zip)

# SD Preperation

1. Insert the SD into your Computer.
2. Copy over the `apps` folder from the `Patched_IOS80_Installer_for_vWii.zip` (after extracting)
3. Copy over the `d2x-cios-installer` folder from `d2x_cIOS_Installer.zip`
4. If not already modded, copy over the contents from Tiramisu.zip to the SD.
5. Copy over the compat_installer.elf file to your wiiu/apps folder.
6. Eject the SD out of your PC and put it in your WiiU.

# NAND Dumping

In case something goes wrong during the modding process, you can use the copies from this dump to restore your vWii.


1. On the Wii U's browser, navigate to wiiuexploit.xyz
3. Click run exploit on the gamepad.
3. Hold B down on the gamepad to enter the NAND Dumper.
4. Use the d-pad on the Gamepad to choose these dump settings:

- Dump SLC: **no**

- Dump SLCCMPT: **yes**

- Dump MLC: **no**

- Dump OTP: **yes**

- Dump SEEPROM: **yes**

5. Press `A` on the Gamepad to dump.
6. After the dumping has ended, power down the Wii U, Eject the SD from your Wii U, and put it in your computer.
7. To keep the NAND Backup safe, move the `slccmpt.bin` and `otp.bin` files to your computer in a safe folder.
8. To save on space, delete The NAND Backup from your SD.
9. Eject the SD from your computer, and insert it in your Wii U.

## Getting the Homebrew Channel

1. When in Tiramisu, launch the Homebrew Channel by opening the Mii Maker.
2. Launch the `compat_installer`
3. Press the `A` button install the Homebrew Channel
4. Wait for the install to finish and then exit the Homebrew Launcher.
5. Launch the vWii by clicking the Wii app.
    - You should have the Homebrew Launcher

## Installing your cIOSes

!> An easy way to brick is having `.wad` files outside of your `apps` folder.

1. Launch the Homebrew Channel
2. Launch the d2x cIOS Installer
3. Select everything EXACTLY as the following
    - Select cIOS: d2x-v11-beta1-vWii
    - Select cIOS base: 56
    - Select cIOS slot: 249
4. Press `A` to install
5. Select everything EXACTLY as the following
    - Select cIOS: d2x-v11-beta1-vWii
    - Select cIOS base: 57
    - Select cIOS slot: 250
6. Press `A` to install
7. Select everything EXACTLY as the following
    - Select cIOS: d2x-v11-beta1-vWii
    - Select cIOS base: 58
    - Select cIOS slot: 251
6. Press `A` to install and `B` to exit

## Patching IOS 80

!> If your Wii U turns off during this process, your vWii will be **bricked**

1. Open the Patched IOS 80 Installer
2. Read the warning screen. It will be on this screen for 30 seconds.
3. Press any button to install
4. Wait until it says `IOS80 Installation is complete!`
5. Press any button to exit 

You're done! Enjoy!

!> Installing anything made for the original Wii such as Priiloader will instantly **brick** your vWii
