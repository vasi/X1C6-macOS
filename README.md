# macOS for ThinkPad X1 Carbon Gen 6

This project is to give the X1C6 a complete and functional build of macOS Sonoma 14 using the guide from [here](https://github.com/tylernguyen/x1c6-hackintosh) with modified ACPI and updated kexts.

Using `MacbookPro15,2` SMBIOS

## My Specs
**Model:** X1C6 [20KG]

**Bios:** 1.63 Vanilla

**CPU:** Intel i7-8550U (0x8086)

**GPU:** Intel UHD620 1536MB (0x5916)

**RAM:** 8GB Dual Channel LPDDR3

**Display:** 14" FHD Non-Touch, 1920x1080, 60Hz

**Storage:** PCIe x4 NVMe Kingston A2000 1 GB SSD

**Partition Type:** APFS

**Wifi:** Intel Wireless AC 8265

**Bluetooth:** Intel Wireless AC 8265

**Bootloader:** OpenCore v1.0.1

**macOS:** Sonoma 14.6

## Note
Your laptop may or may not have the exact specs as mine. Results may vary. If you need help, please ask.

# What Works
- Audio
- Headphone Jack
- Keyboard
- Keyboard Brightness
- Power Management (CPUFriend)
- Battery Manager
- USB A Ports
- USB C Ports
- Trackpad, with full gestures
- Trackpoint
- Webcam
- Microphone
- Display Brightness (needs custom shortcuts)
- Sleep / Wake, but sometimes crashes on wake
- Wifi - Use Heliport
- Bluetooth

# What doesn't work / Haven't tested
- Fingerprint sensor - Touch ID (it will never work)
- HDMI - Haven't Tested
- Thunderbolt 3 - Haven't Tested
- microSD Card Reader - Haven't Tested
- All FN Keys - F7-F12 doesn't do anything

# Pre-Installation
1. Follow tylernguyen's [guide](https://tylernguyen.github.io/x1c6-hackintosh/).
2. Generate SMBIOS for `MacbookPro15,2`

## Credits
- tylernguyen https://github.com/tylernguyen/x1c6-hackintosh
- benbender https://github.com/benbender/x1c6-hackintosh
- zhtengw https://github.com/zhtengw/EFI-for-X1C6-hackintosh
- Rybo713 https://github.com/Rybo713/X1C6-macOS
