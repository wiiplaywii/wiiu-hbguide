# SD Preparation

!> This guide assumes that you have not previously installed any CFW such as Haxchi or CBHC, and that your Wii U has internet access.

!> We are not responsible for bricking your console! Although bricks are rare, they are still very possible!

## You will need
- The latest Tiramisu, obtainable from [here](https://tiramisu.foryour.cafe/)
- Sigpatches, obtainable from [here](https://github.com/marco-calautti/SigpatchesModuleWiiU/releases/latest)
- An SD card. The sweet spot for Wii U SD cards is about 32GB in size, although it will work with anything 2GB or above.
- A computer, laptop, or anything which can read SD cards.

## Installing Files
1️⃣ Insert your SD card into your PC. If you don't have an SD card reader on your computer, buy a USB to SD adapter on Amazon.\
2️⃣ Extract the Tiramisu `.zip` file you downloaded to the root of your SD card.\
3️⃣ Copy the downloaded `01_sigpatches.rpx` file to the following location on your SD card:
```
💾sd:
 ┗ 📂wiiu
   ┣ 📂environments
   ┃ ┣ 📂installer
   ┃ ┃ ┗ 📂modules
   ┃ ┃   ┗ 📂setup
   ┃ ┃     ┣ 📜00_mocha.rpx
   ┃ ┃     ┗ 📜90_launch_installer.rpx
   ┃ ┗ 📂tiramisu
   ┃   ┣ 📂modules
   ┃   ┃ ┗ 📂setup
   ┃   ┃   ┣ 📜01_sigpatches.rpx
```

?> If your computer asks you to overwrite any files, press yes.

And that's it! You've completed step one. Now we're going to hop onto the actual console and install Tiramisu and Aroma.
- **Continue to [Browser Exploit](/browser)**   