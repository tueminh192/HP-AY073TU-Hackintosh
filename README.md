# HP-AY073TU-Hackintosh
Successful install macOS Monterey on HP AY073TU laptop


# OVR:
Stable, fast, high performance

# Specs:

* CPU: i5 5005U
* GPU: HD 5500
* RAM: 8gb DDR3 1600MHZ
* WIFI and Bluetooth : RT8723BE (Replace with ac7260) 
* TouchPad : Synaptics SMBUS
* Audio : ALC282

# ScreenShot
![About](https://github.com/tueminh192/HP-AY073TU-Hackintosh/blob/main/ScreenShot/Preview.png?raw=true)

# Working (All Working)
- [x] Intel Graphics HD 5500
- [x] Power Management for I3 5005U
- [x] Intel Wifi AC7260 (using itlwm kext)
- [x] TouchPad ( Full Gesture : Expose ,...)
- [x] USB Port ( Fully Mapped)
- [x] Function keys
- [x] Icloud
- [x] Hibernation and Sleep
- [x] Brightness control 
- [x] Audio and Audio port
- [x] Ethernet Port 
- [ ] SD Card (Broken)
- [x] HDMI port

# Fixing Wifi
- Download <a href="https://github.com/OpenIntelWireless/HeliPort/releases">HeliPort</a>
- Install HeliPort 
- Set it open with startup

# Adding SMBIOS
- Download <a href="https://mackie100projects.altervista.org/download-opencore-configurator/">Opencore Configurator</a>
- Mount EFI
- Open Config.Plist using Opencore Configurator
- Go to Platform info
- Add MacbookPro12,1 SMBIOS


# Credit
- Special thanks to <a href="https://github.com/acidanthera">Acidanthera</a> for all of those kext
- Special thanks to <a href="https://github.com/zxystd">zxystd</a> for Itlwm, Intel BluetoothFirmware and HeliPort

