## **NOTE:**
This guide can work for almost all modern Samsung devices and not just the S7 FE. 

**The device will be erased completely in order to install the root.**

### Risks of rooting:
1. You can brick your phone by doing this.
2. Can void your warranty. (I suggest rooting after warranty or if your device is a bit old.)
3. KNOX can be tripped and some security features won't be available. (WILL DISABLE SECURE FOLDER)
4. Some apps such as banking apps and calling apps such as Zoom may not work after rooting.

### Things you need:
1. A PC/Laptop.
2. The device you wish to root.
3. An original Samsung cable

### Before starting you should:
- [UNLOCK THE BOOTLOADER](https://xdaforums.com/t/how-to-unlock-bootloader.4244757/)
1. Remove all accounts from the device to ensure security features don't mess our root installation.
2. Turn on usb debugging. If you do not know how to do that, [check here](https://developer.android.com/studio/debug/dev-options).
3. Download [Samsung drivers](https://developer.samsung.com/android-usb-driver) to ensure the device is well connected.
4. This is a tedious process so I suggest charging your device until full.

## **1. Installing the firmware:**
There is a forum for this. Click [here](https://xdaforums.com/t/stock-rom-firmware-where.3716569/).

If you want to use [SamMobile](https://www.sammobile.com/firmwares/) to get the firmware: (you do need to sign up)
1. Go to **Settings > About Device/Tablet > Software Info** and note down the baseband version. This will be required for getting the firmware file.
2. While in **Software Information**, search for "service provider software version" and check the last 3 letters (Device Region). Example: XSA.

## **2. Extracting the MD5 File:**
1. First, you must download [7-zip](https://7-zip.org/) to extract the md5 file. You may use other tools.
2. Then you must extract the files using 7-zip or the software you chose.
3. Next, extract only the files which start with **AP**, **BL**, **CSC**, and **HOME**. (This will take a while depending on the write speed of your storage.)
4. Now transfer the **AP** file to your device. Make sure to put it in **downloads** on your device for easy access.

## **3. Patching AP file with Magisk:**
1. Now, [download the Magisk manager](https://github.com/topjohnwu/Magisk/releases/tag/v26.1) apk.
2. Open the app and click install which is next to Magisk.
3. Click **Select and Patch a File** and select the **AP** file.
4. After patching, you should transfer the patched AP file (it's usually renamed to **Magisk Patched** or something.) to the PC.

## **4. Flashing the patched AP file onto the device:**
1. After the previous steps, [make sure your device is in download mode](https://xdaforums.com/t/guide-how-to-get-into-download-mode.1069032/) and connected to your computer.
2. Now, [download and open the latest version of Odin](https://odindownload.com/).
3. Go to **Options and Disable Auto Reboot**.
4. Click the **AP** button and choose the patched Magisk file.
5. As we added the **AP** file, add the default. (BL, CSC, and HOME)
6. Click **Start**.

## **5. Final steps:**
1. As soon as it finishes, exit out of download mode and immediately [boot into recovery mode](https://www.xda-developers.com/how-to-boot-to-recovery/).
2. Use the volume buttons to go down to **Wipe Data and Factory Reset**.
3. Click the power button and confirm. After this, go back to **reboot now** and click the power button.

## **Once you finish the setup, go to the home drawer and check if the Magisk app is there. If not, shut down the device and turn it on again.**
