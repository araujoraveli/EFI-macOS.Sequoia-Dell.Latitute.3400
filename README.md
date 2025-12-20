<h1 align="center">✨ Perfect Hackintosh ✨</h1>

<h3 align="center">Notebook Dell Latitude 3400</h3>

<p align="center">
  Intel Core i7-8565U (8th Gen Whiskey Lake, UHD 620)
</p>




<img width="2361" height="1395" src="https://github.com/araujoraveli/EFI-macOS.Sequoia-Dell.Latitute.3400/blob/main/Image.png?raw=true" />


## Basic Information

**Latest working macOS**: macOS Sequoia 15.7.2  
**Current OpenCore**: 1.0.6  
**Release date**: 20/12/2025  

---

## Hackintosh Specifications

| Item | Description |
| - | - |
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
| 🔔 Boot Chime | Enabled |
| 🔀 ShowPicker | Enabled, boot timeout 5 seconds |

---

## What works full ✨✅

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
- Sleep / Wake / Lid
- Brightness control keys  
  *(Fn+S / Fn+B as alternative, F11 / F12 also working)*
- All media function keys (F1–F12)
  
---

## What doesn't work ⚠️

- *Hibernation (not supported on Hackintosh systems)*
- *Fingerprint reader (requires Apple T2 chip)*

---

## Observations 🔎

- **Audio codec**, according to official Dell documentation: **Realtek ALC3204**  
  *(functionally compatible with ALC236 layouts)*  
- **Wireless card**: Identified via physical label on the Intel module — **PCIe 9462NGW (CNVi)**
- **SD card reader**: mapped as internal USB device
- **Bluetooth**: mapped as internal USB device
- **Fingerprint reader**: mapped as internal USB device to avoid system error logs  
  *(non-functional, as fingerprint readers are not supported on Hackintosh systems)*

---

## Special Notes ✨🚀

**Developed on a 100% factory-original (OEM) notebook, with zero hardware modifications, showcasing the potential of a clean, stable, and carefully engineered Hackintosh.**

An extremely clean setup, free from unnecessary components — only what is strictly required and fully functional.  

All fine-tuning and low-level adjustments were meticulously implemented through **DeviceProperties** and other sections of `config.plist`, with no hacks or workarounds, strictly adhering to official documentation and industry best practices.  

The system is fast, smooth, and rock-solid, delivering a user experience virtually indistinguishable from a real MacBook — a **true, near-perfect Hackintosh**.

---

## References / Credits

- [Dortania – Coffee Lake & Whiskey Lake Laptop Guide](https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/coffee-lake.html)
- [Universo Hackintosh – Intel 8th Gen Base EFI](https://github.com/luchina-gabriel/BASE-EFI-INTEL-8THGEN-COFFEE-LAKE-PUBLIC)
