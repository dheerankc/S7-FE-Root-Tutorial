[B]NOTE : This guide can work for almost all modern Samsung devices and not just the S7 FE. [/B]

The device will be erased completely in order to install the root.

[B]Risks of rooting : [/B]
1. You can brick your phone by doing this.
2. Can void your warranty. (I suggest rooting after warranty or if your device is a bit old.)
3. KNOX can be tripped and some security features won't be available. ( [B]WILL DISABLE SECURE FOLDER[/B] )
4. Some apps such as banking apps and calling apps such as Zoom may not work after rooting.

[B]Things you need : [/B]
1.  A PC/Laptop.
2. The device you wish to root.
3. An original Samsung cable

[B]Before starting you should :[/B]
[SIZE=5][B]- [/B][/SIZE][URL='http://UNLOCK THE BOOTLOADER.+https://xdaforums.com/t/how-to-unlock-bootloader.4244757/'][SIZE=5][B]UNLOCK THE BOOTLOADER[/B][/SIZE][/URL][SIZE=5][B].[/B][/SIZE]
1. Remove all accounts from the device to ensure security features don't mess our root installation.
2. Turn on usb debugging. If you do not know how to do that, [URL='https://developer.android.com/studio/debug/dev-options']check here[/URL].
3. Download [URL='https://developer.samsung.com/android-usb-driver']Samsung drivers[/URL] to ensure the device is well connected.
4. This is a tedious process so i suggest charging your device until full.

[SIZE=6][B]1. Installing the firmware. [/B][/SIZE]
There is a forum for this. Click [URL='https://xdaforums.com/t/stock-rom-firmware-where.3716569/']here[/URL].

[B]If you want to use [/B][URL='https://www.sammobile.com/firmwares/'][B]SamMobile[/B][/URL][B] to get the firmware : (you do need to sign up)[/B]
1. Go to [B]Settings > About Device/Tablet > Software Info [/B]and note down the baseband version. This will be required for  getting the firmware file.
2. While in [B]Software Information[/B], search for "[B]service provider software version[/B]" and check the last 3 letters (Device Reigon). Example : XSA.

[B][SIZE=6]2. Extracting the MD5 File.[/SIZE][/B]
1. First you must download [URL='https://7-zip.org/']7-zip[/URL] to extract the md5 file. You may use other tools.
2. Then you must extract the files using 7-zip or the software you chose.
3. Next, extract only the files which start with a [B]AP[/B],[B] BL[/B], [B]CSC[/B] and [B]HOME[/B]. (This will take a while depending on the write speed of your storage.)\
4. Now transfer the [B]AP[/B] file to your device. Make sure to put it [B]downloads[/B] on your device for easy access.

[SIZE=6][B]3. Patching AP file with Magisk.[/B][/SIZE]
1. Now, [URL='https://github.com/topjohnwu/Magisk/releases/tag/v26.1']download the Magisk manager[/URL] apk.
2. Open the app and click install which is next to Magisk.
3. Click [B]Select and Patch a File [/B]and select the [B]AP [/B]file.
4. After patching, you should transfer the patched AP file (its usually renamed to [B]Magisk Patched[/B] or something.) to the pc.

[SIZE=5][B]4. Flashing the patched AP file onto the device.[/B][/SIZE]
1. After the previous steps, [URL='https://xdaforums.com/t/guide-how-to-get-into-download-mode.1069032/']make sure your device is in download mode[/URL] and connected to your computer.
2. Now, [URL='https://odindownload.com/']download and open the latest version of Odin[/URL].
3. Go to [B]Options and Disable Auto Reboot[/B].
4. Click the [B]AP[/B] button and choose the patched magisk file.
5. As we added the AP file, add the default. (BL, CSC and HOME)
6. Click [B]Start[/B].

[SIZE=5][B]5. Final steps[/B][/SIZE]
1. As soon as it finishes, exit out of download mode and immediately [URL='https://www.xda-developers.com/how-to-boot-to-recovery/']boot into recovery mode[/URL].
2. Use the volume buttons to go down to [B]Wipe Data and Factory Reset[/B].
3. Click the power button and confirm. After this, go back to [B]reboot now[/B] and click the power button.

[SIZE=6][B]Once you finish the setup, go to the home drawer and check if the magisk app is there.
If not, shut down the device and turn it on again.[/B][/SIZE]
