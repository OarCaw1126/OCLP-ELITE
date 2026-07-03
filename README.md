📌 Hackintosh And Legacy MACS is already history.

* This project was archiviving on September 6, 2026.
* Thats Means NO GOLDEN GATTE PROBALLY TESTING BETA KEXTS AND END OF ERA FOR OCLP
* 📢 Important notice for users:
* The Latest Version to Support OCLP ELITE Is 4.0.1


<div align="center">
             <img src="docs/images/OC-Patcher.png" alt="OpenCore Patcher Logo" width="256" />
             <h1>OCLP ELITE</h1>
</div>

OCLP ELITE is an OCLP that has functions from OCLP PLUS and some from OCLP MOD


It supports everything from Big Sur to Tahoe Patches like Wi-Fi, audio, graphics acceleration and camera

## 🛎️ Features

 Full macOS Tahoe Support
Modern root patching support for macOS Tahoe 26.0 (25A5316i) and later versions.

You Dont Get Patch Error For Volume Dirty
Thankfully You Dont Have To Unpatch To Continue

## Supported Macs/Hackintosh

* iMac: 2007-2019
* MacBook: 2008-2017
* MacBook Pro: 2008-2019
* MacBook Air: 2008-2020
* Mac Pro: 2009-2013
* Mac Mini: 2009-2018
* iMac Pro: 2017
* Any Hackintosh Works

## ❌Non-functional features
On majority of patched Macs, iPhone Mirroring and Apple Intelligence won't be functional.

iPhone Mirroring requires T2 for attestation and Apple Intelligence requires an NPU only found in Apple Silicon.
The patcher is unable to provide a fix for these as they're hardware requirements.

Only iPhone Mirroring Are Compatible Of This Macs

* iMac 2019
* Macbook Pro 2018-2019
* MacBook Air 2018-2020
* Mac Mini 2018

## Requierements

* An Usb Minimun 32GB+

* Minimun 4gb Of Ram To Run Tahoe

* macOS Catalina Installed To Install It

## ⬇️⬇️ How To Insttall

1. Go To Create macOS Installer and go to Download macOS Installer

2. Install An Version Whattaver You Want Select Stable Or Beta

3. Now If Shows Alert Finally Go To Yes Or Ok

4. Backup Yor Usb (optional)

5. Go Your Installer And Usb And Click Yes This Will Be Delete All Your Data On Your USB

6. Next Click Yes Or Build And Insttall Opencore Select Your Usb Partition and Restart

7. Hold The Alt/option Key Since Your Mac Is Booting Go To Efi Boot And Install Macos (Version)

8. Install Tahoe On YOur Laptop

9. Click Build And Install Opencore Install Opencore Click On YOur Disk Efi And Restart

## 🩹🩹 HOW TO PATCH

HOW TO PATCH GRAPHICS 🔧🔧🔧🔧

If You Patch Without A Metallib You Get The Error No Metallib Found On Your macOS Version

1. Install A [Metallib](https://github.com/pyquick/MetallibSupportPkg/releases)

2. Open OCLP ELITE App

3. Go To Post Install Root Patch And Start Root Patching Next Select Ignore

4. Install [OCAT](https://github.com/ic005k/OCAuxiliaryTools/releases/download/20250001/OCAT_Mac.dmg) Select Your Internal Disk Efi Mount (disk0s1) And Open config.plist Deactivate amfi on Kexts now go to NVRAM > ADD 7C436110-AB2A-4BBB-A880-FE41995C9F82 > bootargs And Put This Text "amfi=0x80 dart=0"  Ensured there are no duplicates of either the amfi=0x80 or the dart=0  and click save or press command/Cmd s And Restart And Done

HOW TO PATCH AUDIO 🔊🔊🔊

1. Go To OCLP ELITE App

2. Go To Root Patch And If there's audio, patch it.

3. If Theres Install Kdk To Continue Without WiFi Please Install A [KDK](https://github.com/dortania/KdkSupportPkg/releases) Depends Of Your Build Version

HOW TO PATCH WIFI 🛜🛜🛜

1. Go To OCLP ELITE App

2. Go To Root Patch And If there's Only WiFi patch it If Theres WiFi, Audio And Other Dont Patch It.

3. Install [OCAT](https://github.com/ic005k/OCAuxiliaryTools/releases/download/20250001/OCAT_Mac.dmg) Select Your Internal Disk Efi Mount (disk0s1) And Open config.plist Deactivate amfi on Kexts now go to NVRAM > ADD 7C436110-AB2A-4BBB-A880-FE41995C9F82 > bootargs And Put This Text "amfi=0x80 dart=0" Ensured there are no duplicates of either the amfi=0x80 or the dart=0 and click save or press command/Cmd s And Restart And Done

How Know Patches Are Alreade Installed

Check Audio On Your Keyboard


## 📜 Credits
*   [`Acidanthera`](https://github.com/Acidanthera) (OpenCorePkg, Lilu, etc.)
*   [`Dortania Team`](https://github.com/dortania) (Original OCLP authors)
*   [`lzhoang2801`](https://github.com/kgp-macPro/OCLP-lzhoang2801) (Original Tahoe patchset)
*   [`CloverHackyColor`](https://github.com/CloverHackyColor) (Hackintosh essentials and beyond)
*   [`YBronst`](https://github.com/YBronst) (Developer and optimizer of tools for macOS Tahoe26.x)
*   [`Torxed`](https://github.com/OarCaw1126) (Developer And Support Legacy Macs)
*   [`laobamac`](https://github.com/laobamac) (Developer OCLP-Mod, Chinese language)
*   [`crystall1nedev`](https://github.com/crystall1nedev) (Eva Isabella Luna)
*   [`pycuick`](https://github.com/pyquick) (Developer To Metallib For Graphics Support macOS 26)
*   *Full list of OCLP contributors can be found in the [`original repository`](https://github.com/dortania/OpenCore-Legacy-Patcher).*
