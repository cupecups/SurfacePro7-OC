# SurfacePro7-OC
This project aims to provide continued support running macOS on the Surface Pro 7
<br>
<br>
<br>
![alt text](https://github.com/cupecups/SurfacePro7-OC/blob/a9667297b9876673145e5660ea4125db86932cd3/ss/sequoia.PNG)
![alt text](https://github.com/cupecups/SurfacePro7-OC/blob/a9667297b9876673145e5660ea4125db86932cd3/ss/tahoe.PNG)

## Specifications:

| Model: | Pro 7 |
|---|----------|
|CPU| 10th Gen i7 |
|GPU| Intel UHD (unsupported)/ Intel Iris Pro |
|RAM| 16 GB |
|SSD| 512GB NVME |
|WiFi| Intel Wifi |
|Bluetooth| Intel Bluetooth |
|Batt| XX,000 mAH |
|USB| 1x USB-C |
|USB| 1x USB-A |


## What works 
- Surface Pro i5 & i7 Supported (i3 Unsupported Graphics)
- macOS Installer
- macOS Updates
- Fan
- USB
- Trackpad
- TouchScreen
- Keyboard
- Audio
- Brightness Keys
- Power Management
- UEFI Secure Boot ON
- Surface Keyboard Hot Plug
- Intel Wifi
- Intel Bluetooth
- Battery Status
- Dual Boot with Windows
- Dual Boot with Linux
- Dual Boot with ChromeOS
- SD card
- Volume Buttons
- Power Button
- Recovery
- Surface Pen
- USB-C video out
- FileVault
- Sleep/Hibernation (Hibernatemode 25 only)
- Surface Dock

## What doesn't work
- Accelerometer (unsupported device)
- Cameras (unsupported device)
- Hardware based DRM (Apple Issue)

### [guide by @balopez83) Quirks & Fixes - Includes how to set up the Touch Screen](https://github.com/balopez83/Surface-Pro-7-Hackintosh/blob/main/3-quirks%26fixes.md)

### [guide by @balopez83) Enable Secure Boot with OpenCore/macOS](https://github.com/balopez83/Surface-Pro-7-Hackintosh/blob/main/7-SecureBootOn.md)

## for better performance on tahoe beta remove liquidass effect
- drag'n drop the FeatureFlags.zip under /Library/Preferences/ (You can cmd+shift+g and type /Library/Preferences/ in Finder).
- Double-click to decompress, reboot, done

## For people having issues with FV in Tahoe, you could try this:

1. disable EnableJumpstart in config.plist > UEFI > APFS

2. download apfs_aligned.efi from here.

3. place it into OC > Drivers

4. add it to config.plist, as well.

5. reboot and see if you can login.

##enable launchpad tahoe
lauchback [@trey-a-12](https://github.com/trey-a-12/LaunchBack)

## Credits
Special thanks to [@Xiashangning](https://github.com/Xiashangning) & [@balopez83](https://github.com/balopez83) for the excellent work done on his BigSurface kext. @badstorm & @Xiashangning for the initial work they did in getting initial support for macOS on the Surface Pro 7 from which my work builds upon. 

