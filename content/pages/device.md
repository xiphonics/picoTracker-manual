---
title: Device Management
template: page
---

The device screen allows you to manage settings for the picoTracker device hardware itself.

**Note:** the picoTracker saves its device settings to the SDCard so if you replace the sdcard in your picoTracker, the device configuration will reset to factory defaults.

![](device screen example screenshot)

## MIDI

- **midi:** Lists the picoTracker MIDI interfaces available (currently only TRS output is supported)
- **midi sync:** Options to enable different settings for MIDI clock sync messages output.

## Color Themes

The color scheme for the picoTracker can be customised and saved. 

The following colors can be configured and are listed with their default setting as well as a note on the colors use in the picoTracker user interface:

| Name | Default | Use
| -------- | ------- | -------
BACKROUND|0F0F0F
FOREGROUND|ADADAD|text and cursor in cursor
HICOLOR1|846F94|row count in song screen
HICOLOR2|6B316B|inverted highlight, eg. "Song" screen label 
INFOCOLOR|33EE33|information displays eg. used for battery gauge ok level
WARNCOLOR|11EE22|warning displays eg. battery gauge low level
ERRORCOLOR|FF1111|error displays eg. battery gauge critical level
CURSORCOLOR|224400|??
CONSOLECOLOR|99FFAA|??

## Updating Firmware

The picoTracker firmware can be easily updated by powering the picoTracker via a USB connected to a PC. Select `Update firmware`. This will reboot the device into *BOOTSEL* mode, and you'll see the picoTracker show up as a USB mass storage device on the connected computer. At that point, just copy the UF2 firmware file into the USB device as you would with a USB stick or USB drive. 

Once copying (flashing) of the new firmware is completed, the picoTracker will automatically reboot and be running the newly installed firmware.
