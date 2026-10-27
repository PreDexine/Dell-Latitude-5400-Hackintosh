# Dell Latitude 5400 Hackintosh
OpenCore EFI configuration to boot MacOS Sequoia (might also support for older MacOS) on Dell Latitude 5400. \
Using OpenCore version 1.0.8 and currently it's still on progress.

> [!NOTE]
> **This project is shared only for my side hobby just for fun and not intended for a serious project.*

## Dell Latitude 5400 Specifications
| **Components** | **Name** |
| -------------- | -------- |
| **CPU** | Intel Core i5 8265U |
| **GPU** | Intel UHD Graphics 620 |
| **RAM** | 1x8GB DDR4 |
| **Storage** | 256GB NVME |
| **Ethernet** | Intel Gigabit I219-V |
| **Wi-Fi** | Intel Wireless AC 9560 |
| **Audio** | Realtek ALC3204 |
| **Display** | Full HD 1920 x 1080 |

## Current Status
- Everything works smoothly.
- Keyboard and trackpad works.
- Wifi is supported without Heliport.
- LAN work fine.
- GPU metal 3 supported.

## Small Issues
- Brightness key function not work (use Fn+S and Fn+B to adjust brightness).
- Bluetooth still not working (still need some fix).
- HDMI still not tested (will try asap).
- MicroSD slot still not tested (might need some kext for this).
- WWAN not tested as i don't have the card (not sure if this still work on newer macos).

## Next Progress
- Support for MacOS Tahoe (might not be planned).
- Fixing some issues if found.
- Try to login with real Apple Account.
- Secure boot support? (not sure).

**Will keep this project updated until everything works normally but, don't expect for this project to be updated daily.**
