# Dell Latitude 5400 Hackintosh
OpenCore EFI configuration to boot MacOS Sequoia on Dell Latitude 5400. \
Using OpenCore version 1.0.8.

> [!NOTE]
> **Since this is only a dumb project by me to try hackintoshing my Dell Latitude 5400 because why not? I'll be not updating the OC EFI file anymore. But the last updated EFI file is ready to use anyway.**

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
| **OS** | MacOS Sequoia |

## What's Working
- iGPU hardware acceleration.
- Keyboard and trackpad including gestures.
- Native Wi-Fi without heliport.
- Onboard LAN.
- Built-in speaker.
- Built-in webcam.

## What's not working
- HDMI output (not sure about the type c DP output).
- Bluetooth.
- MicroSD slot.
- Hibernation.
