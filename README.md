**MacOS Monterey:**
![image](https://user-images.githubusercontent.com/1530031/202322619-3f677d15-7458-4052-91da-5c9406388f92.png)

**MacOS Ventura**
![image](https://user-images.githubusercontent.com/1530031/202323451-9fce4f32-3da9-4e6c-bb32-1d79a4d65639.png)

## Hardware

**Case:** SSUPD Meshilicious <br />
**Operating System:** MacOS Ventura 13.0.1 <br />
**Multi-Boot:** Windows 10, MacOS Ventura <br />
**Bootloader:** OpenCore 0.85 <br />
**SMBIOS:** Mac Pro (2019) <br />
**CPU:** AMD Ryzen 5950X <br />
**GPU:** AMD Radeon RX 6800XT <br />
**RAM:** 64GB - 2x Corsair Vengeance RGB 3600 MHZ - F4-3600C18-32GTZR <br />
**Motherboard:** Asus ROG B550-I <br />
**Audio Codec:** Asus ALC-S1220A <br />
**Ethernet Card:** Intel(R) Ethernet Controller I225-V - 2.5GB Ethernet <br />
~~**Wifi/BT Card:** Intel® Wi-Fi 6 AX200~~ <br />
**Wifi/BT Card:** Fenvi BCM94360NG M.2 Wi-Fi Card <br />
**BIOS revision:** v2803 <br />
**Mouse:** Razer Mamba Tournament Edition <br />
**Keyboard:** Corsair Gaming K70 RGB Rapidfire, Apple Keyboard (Wired and Bluetooth) <br />
**Touchpad:** Razer Firefly <br />
**Webcam:** Logitech C922 <br />
**Microphone:** Blue Yeti, Apple Airpods, Apple wired earphones (USB-C, and 3.5mm), Hyper-X Cloud II (USB-A, and 3.5mm) <br />
**Headphones/Earphones:** Bose QC35 II, Apple Airpods, Apple wired earphones (USB-C, and 3.5mm), Hyper-X Cloud II (USB-A, and 3.5mm) <br />
**Speakers:** Bose® Companion® 2 Series III Multimedia Speaker System (3.5mm) <br />
**Storage:** 2x Samsung 970 Pro NVMe SSD <br />
**Printer:** Canon TS9100 <br />
**Cooling:** Kraken Z63 280mm <br />

## What's working:

- Keyboard
- Mouse
- Webcam
- Earphones/Headphones/Speakers/Dedicated Mic/Input (USB-C, USB-A, and 3.5mm)
- Earphones/Headphones/Speakers/Output (USB-C, USB-A, and 3.5mm)
- Bluetooth 4 (BCM94360NG)
- Wifi 2.4Ghz + 5Ghz (BCM94360NG)
- Ethernet (Intel I225-V - Tested with 1.5GB Down, 1.0GB Up - CAT8)
- iMessage
- Handoff
- iCloud & iCloud Sync
- FaceTime (Both Phone Calls & Videos)
- Printer: AirPrint & Bonjour
- Discord App (required to be launched with `MKL_DEBUG_CPU_TYPE=5` Environment Variable)
- Screen Sharing (Tested with iPad 15.4.1 and iPhone 15.5 [Shared Device screen to Computer])
- Power management
- Sleep & Hibernation
- GPU & Graphics Acceleration & DRM (Tested Netflix & Apple TV + both in Chrome with Widevine + Safari, 4K, 1440p, and 1080p)
- USB (All Ports work perfectly out of the box without USBMap, but I mapped them anyway to learn)
- Peripherals: PS5 Controller (tested with PlayStation Remote Play)
- PBO
- XMP
- Cooling AIO

## What could work (with minor changes):
- Wifi 6 (Intel I225-V, Requires AirportItlwm.kext)
- Bluetooth 5 (Intel I225-V, Requires BlueToolFixup.kext)

## What's not working:
- Side-Car (Sharing Screen to Device. Does not work even with FeatureUnlock.kext)
