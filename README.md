bq Aquaris 5 HD - CyanogenMod 11 (Android 4.4.4)
==============

### Compilation guide:

     * repo init -u git://github.com/CyanogenMod/android.git -b cm-11.0

     * repo sync 

     * git clone https://github.com/cakehonolulu/android_vendor_bq_Aquaris5HD vendor/bq/Aquaris5HD

     * You should also follow the guide of https://github.com/cakehonolulu/android_device_bq_Aquaris5HD in order to get the device folder on your source

     * . build/envsetup.sh

     * brunch Aquaris5HD

### What's working:

 * Sound
 * CPU Frequency Scaling
 * No Hard-Reboots
 * Graphics
 * Storage
 * Battery meter
 * WI-FI
 * Audio
 * Camera
 * Flashlight

### What's not working:

 * HWComposer
 * Brightness/Autobrightness
 * Microphone
 
### What is not tested:

 * SIM1/2 RIL [Data Connection and Calls] (Not tested)
 * GPS/A-GPS

### Thanks to:

 * Pablito2020
 * pawitp
 * dhacker29
 * sultanxda
 * chrmhoffmann
 * kashifmin
 * andreya108
 * andr7e
 * blackrebel75