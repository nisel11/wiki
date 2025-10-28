---
slug: /devices/alioth
pagination_next: null
pagination_prev: null
title: "POCO F3 / Mi 11x / Redmi K40 (alioth)"
---

# POCO F3 / Mi 11x / Redmi K40 (alioth)
:::info
## Device Information

- **Device:** POCO F3 / Mi 11x / Redmi K40
- **Release Date:** March 27, 2021
- **Chipset:** 	Qualcomm SM8250 Snapdragon 870 5G
- **RAM:** 6 GB / 8 GB
- **Storage:** 128 GB / 256 GB
- **Battery:** 4520 mAh
- **Display:** 6.67 inches, AMOLED, HDR10+, 120Hz, 1080 x 2400 pixels
- **Rear Camera:** Triple 48 MP (main) + 8 MP (ultrawide) + 5 MP (telephoto macro)
- **Front Camera:** 20 MP (wide)
- **Halcyon Version:** Bloom
- **Maintainer:** bntxperses
:::

<a href="https://get.hlcyn.co/builds/alioth/" class="button button--primary">Get builds</a>

## Installation Guide
:::caution
Make sure to backup your data before proceeding.
:::

### Installing Recovery
1. Enter fastboot mode by using a key combination `Power + Vol Down`.
2. Connect your device to your PC via USB.
3. Verify that your PC detects the device with `fastboot devices`.
4. Flash the boot image onto your device using `fastboot flash boot boot.img`.
5. Flash the vendor boot image onto your device using `fastboot flash vendor_boot vendor_boot.img`
6. Reboot into recovery mode by typing `fastboot reboot recovery` in command line.

### Installing ROM
1. Download the latest release of Halcyon.
2. Reboot into recovery mode.
3. Perform a Format data.
4. Return to the main menu.
5. Select Apply update > Apply from ADB.
6. Now you can start sideloading by this command:
```
adb sideload halcyon_alioth-xxxxx.zip
```

## Troubleshooting

If you encounter any issues during or after the installation, feel free to ask to our chat group for solutions to common problems.
