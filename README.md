Hi this is Opencore 0.6.8 EFI file of my Dell E5430.

Tested running macOS Catalina & BigSur Perfectly.
------------------------------------------------------------
Detail Laptop Specification:
Brand & Series   : Dell Latitude E5430
Processor        : Intel Core i5 3210M
iGPU             : Intel HD Graphics 4000 (1366x768)
Audio Codec      : IDT92HD93BXX
Trackpad         : Dell Taouchpad ALPS
Bluetooth        : Dell Wireless 380
Wifi             : Atheros AR5B91
Ethernet         : Broadcom 57XX
------------------------------------------------------------
What's working :
* Sleep, restart, shutdown.
* CPU Power Management
* Wifi
* Bluetooth
* All USB port
* Brightness UP/Down
* Touchpad
* Battery Indicator
* VGA Out (Must be connecting from first boot by pressing Fn+F8 before booting to MacOS)
* iCloud
------------------------------------------------------------
Not Tested yet :
+ Ethernet
+ HDMI out
+ Airdrop
+ Handoff
____________________________________________________________
Source :
This EFI originally made by "osx86-ijb" link : 
https://github.com/osx86-ijb/Dell-Latitude-e5430-3rd-Gen-Core-i5-3210m-macOS-BigSur

I made some modifications to meet my hardware configuration.
What has been change :
* update open core version to 0.6.8
* SSDT Patch
* Replace Wireless Kext
* insert (HoRNDIS.KEXT SMCDEllSensors.KEXT)

