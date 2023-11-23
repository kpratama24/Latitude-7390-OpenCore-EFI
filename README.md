# Dell Latitude 7390 - OpenCore Configuration

<img align="right" src="https://github.com/halal-beef/res/blob/main/latitude.png" alt="macOS Ventura running on the Latitude 7390" width="425">


[![macOS](https://img.shields.io/badge/macOS-Ventura-orange.svg)](https://developer.apple.com/documentation/macos-release-notes)
[![macOS](https://img.shields.io/badge/macOS-Sonoma-brightgreen.svg)](https://developer.apple.com/documentation/macos-release-notes)
[![OpenCore](https://img.shields.io/badge/OpenCore-0.9.5-blue)](https://github.com/acidanthera/OpenCorePkg)
[![License](https://img.shields.io/badge/license-MIT-purple)](/LICENSE)

<p align="center">
   <strong>Status: Maintained</strong>
   <br />
   <strong>Version: </strong>0.3 rev 1
  </p>
</p>
</br>

## 💻 Hardware Configuration

| Category  | Component                            |
| --------- | ------------------------------------ |
| CPU       | Intel Core i7-8650U                  |
| GPU       | Intel UHD Graphics 620               |
| SSD       | Western Digital PC SN720 NVME        |
| Memory    | 8GB DDR4 2400Mhz                    |
| WiFi & BT | Broadcom BCM94360             |

## ❗ Post Installation

#### Fixing crackly audio coming from the headphone port

- Open the Terminal 
- cd into the "ComboJack_Installer" folder
- Type ./install.sh and type in your password when asked
- Reboot

#### Enable HiDPI mode (optional)

- Open the Terminal 
- Run this script in Terminal
```bash
bash -c "$(curl -fsSL https://raw.githubusercontent.com/xzhih/one-key-hidpi/master/hidpi.sh)"
```
- Follow the steps

## 🛠️ Status

- [X] WiFi & Bluetooth (No kext and modification needed. Works OOB with native Apple Card)
- [X] AirDrop, Handoff, and other Native Continuity Features (I replace the Intel Wi-Fi card with Broadcom Chip that's natively supported by Apple)
- [X] Brightness / Volume Control
- [X] Battery Information
- [X] Audio (Audio Jack & Speaker)
- [X] Internal Microphone
- [X] USB Ports & Built-in Camera
- [X] Graphics Acceleration
- [X] Trackpoint / Touchpad
- [X] Touchpad Buttons
- [X] Power management / Sleep
- [X] FaceTime / iMessage (iServices)
- [X] HDMI
- [X] Automatic OS updates
- [X] USB-C

## 📜 Credits

- [halal-beef](https://github.com/halal-beef) ```For the base OpenCore EFI```
- [valnoxy](https://github.com/valnoxy) ```For the README Template```
- [AlbinoGiraffe](https://github.com/AlbinoGiraffe) ```For the SSDT-GPI0.aml```
- [dortania](https://github.com/Dortania) ```For the OpenCore guide```
