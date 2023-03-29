# deskmeet_x300_r5_5500_rx570_8g_opencore

Hackintosh (Ventura 13.3) EFI for ASRock DeskMeet X300

## My Hardware

* CPU: AMD Ryzen R5 5500
* Graphics Card: AMD Radeon RX570 8G (HP OEM)
* Motherboard: ASRock X300 ITX
* Wi-Fi & Bluetooth: Broadcom BCM 94352z
* Network Adapter: Realtek RTL8111H
* Audio Card: Realtek ALC897 (AppleALC Layout: 12)

## Tested macOS Version

macOS Ventura  (13.3)

## Compatibility

* AMD Ryzen Series (modify kernel-patch if not 6-core)
* ASRock Deskmeet X300
* Broadcom BCM 94352z (you can switch to Intel by adding responding kexts)

## What Works

* Video Acceleration
* Audio
* USB ports
* CPU Power Management (via AMDRyzenCPUPowerManagement)
* Hibernation
* WiFi
* Bluetooth
* Airdrop
* LAN
* iMessage/Facetime
* Handoff
* Universal Clipboard

## What will never Work

* Things do not work with AMD Vanilla (such as AppleHV, some Adobe softwares, etc)

## BIOS Settings

* Turn on: AMD SVM, IOMMU, SR-IOV, Above 4G Decoding, WHQL Driver

* Turn off: CSM, ResizableBar


# SMBios Settings

* Suggested Model: MacPro7,1
* **This EFI does not contain Model Settings, you need to add it by OC Configurator before first boot**