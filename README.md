# Flashing Guide

### Requirements
The latest Android 16 firmware, an [unlocked bootloader](https://github.com/spike0en/nothing_archive#ii-unlocking-bootloader-) and USB debugging enabled from developer options.

The latest ROM .zip package and boot, super_empty and vendor_boot .img files for Tetris available [here](https://sourceforge.net/projects/voltage-os/files/Tetris/recovery/) or [here](https://blissroms.org/downloads/Tetris).

The latest version of [Google's platform-tools](https://developer.android.com/tools/releases/platform-tools?hl=en#downloads) and a computer.

### First flash steps
Reboot to bootloader
```
adb reboot bootloader
```

Flash LineageOS recovery
```
fastboot flash boot boot.img
fastboot flash vendor_boot vendor_boot.img
fastboot wipe-super super_empty.img
```

Reboot to recovery
```
fastboot reboot recovery
```

Do a factory reset (Factory Reset > Format data / factory reset)

Sideload the rom .zip package (Apply Update -> Apply from ADB)
```
adb sideload rom-packagename.zip
```

Reboot to System

### Manually updating from recovery
Reboot to recovery
```
adb reboot recovery
```

Sideload the rom .zip package (Apply Update -> Apply from ADB)
```
adb sideload rom-packagename.zip
```

Reboot to System
