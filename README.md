# Hackintosh Dell Latitude 3400 – Intel Core i7-8565U (8th Gen Whiskey Lake, UHD 620)

<img width="2361" height="1395" src="https://github.com/araujoraveli/EFI-macOS.Sequoia-Dell.Latitute.3400/blob/main/Image.png?raw=true" />

## Basic Information

**Latest working macOS**: macOS Sequoia 15.7.2  
**Current OpenCore**: 1.0.6  
**Release date**: 20/12/2025  

---

## Hackintosh Specifications

| Item | Description |
|-----|:-----------:|
| 💻 Type | Notebook |
| 🖥️ Vendor / Model | Dell Latitude 3400 |
| ℹ️ BIOS | F24 |
| ⚙️ Processor | Intel® Core™ i7-8565U (8th Gen Whiskey Lake) |
| 🔩 Memory | 2×8 GB DDR4 2400 MHz (16 GB RAM) |
| 🎮 iGPU | Intel® UHD Graphics 620 (Vendor ID: 0x8086, Device ID: 0x3E9B) |
| 🎧 Audio Codec | Intel Cannon Point-LP PCH (Realtek ALC236 / ALC3204 compatible) |
| 🌐 Ethernet | Realtek PCIe GbE Family Controller (RTL8111) |
| 🛜 Wireless / BT | Intel Dual-Band Wireless-AC 9560 (Wi-Fi) + Bluetooth 5.0 |
| 🖱️ Trackpad | I2C HID Precision Touchpad – Dell (VEN_DELL&DEV_08BC) |
| ⌨️ Keyboard | Dell PS/2 Keyboard |
| 💾 Storage | Kingston SA400S37 480 GB (SATA III) |
| 🧬 SMBIOS | MacBookPro15,2 |

---

## What works

- Bluetooth (Intel, 5.0)
- WLAN (itlwm.kext + HeliPort.app)
- Ethernet (RealtekRTL8111.kext)
- HDMI and USB-C DisplayPort Alt Mode (with audio)
- Full graphics acceleration
- USB ports (USB-A and USB-C mapped, working after sleep)
- Trackpad with multi-touch gestures
- Trackpad physical buttons
- Audio (internal speakers and microphone)
- Combo audio jack (cold plug and hot plug)
- Webcam (720p)
- Sleep / Wake
- Brightness control keys  
  *(Fn+S / Fn+B as alternative, F11 / F12 also working)*

---

## What doesn't work

- *Hibernation (not supported on Hackintosh systems)*
- *Fingerprint reader (requires Apple T2 chip)*

---

## Notes

- **Audio codec** according to official Dell documentation: **Realtek ALC3204**  
  *(functionally compatible with ALC236 layouts)*  
- **Wireless card** according to Intel board ticket: **PCIe 9462NGW / CNVi**

---

## References / Credits

- [Dortania – Coffee Lake & Whiskey Lake Laptop Guide](https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/coffee-lake.html)
- [Universo Hackintosh – Intel 8th Gen Base EFI](https://github.com/luchina-gabriel/BASE-EFI-INTEL-8THGEN-COFFEE-LAKE-PUBLIC)
