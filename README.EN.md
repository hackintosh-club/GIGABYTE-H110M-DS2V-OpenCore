## GIGABYTE H110M DS2V Hackintosh OpenCore EFI

![image](ScreenShot/H110MDS2V.png)

### [简体中文](https://github.com/hackintosh-club/GIGABYTE-H110M-DS2V-OpenCore)

### OpenCore

[OpenCore 0.9.5](https://github.com/acidanthera/OpenCorePkg)

### OS Version Tested

- macOS Monterey 12.x
- macOS Ventura  13.x

### Hardware

- Motherboard: H110
- Bios Version:  F21 06/09/2017
- CPU: Intel 7th  i3-7100
- RAM: Kingston 8GB DDR4 2400Mhz
- SSD: Kingston SATA SSD 120G Windows
- SSD: Kingston SATA SSD 240G MacOS
- iGPU: Intel HD Graphic 630 (VGA & DVI output)
- Audio: Realtek ALC887
- Ethernet Card: Realtek RTL8168/8111
- WIFI: No WiFi Adaper

### Notes

 - Use [OpenCore Configurator](https://mackie100projects.altervista.org/opencore-configurator/) or [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools) build your SMBIOS

### Bios Setup

```
BIOS
     |-- Fast Boot：Disabled
     |-- Windows 8/10 Fetures：Other OS
     |-- CSM Support：Disabled
     |-- Storage Boot Option Control：UEFI
     |-- Other PCI devices：UEFI

Peripherals
	   |-- USB Configuration
	      |-- Leacy USB Support：Enabled
	      |-- XHCI Hand-off：Enabled
	   |-- SATA And RST Configuration
	      |-- SATA Mode Selection：AHCI
Chipset		
     |-- VT-d：Disabled
     |-- Internal Graphics：Enabled
     |-- DVMT Pre-Allocated：64M
     |-- DVMT Total Gfx Mem：MAX
     |-- IOAPIC 24-2119 Entries：Disabled
```

### Contact Us

QQ Group: 23304408

![image](ScreenShot/QRCode.png)


### Tools

- [Hackintool](https://github.com/headkaze/Hackintool) 
- [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools) AKA `OCAT`.
- [OpenCore Configurator](https://mackie100projects.altervista.org/opencore-configurator/) AKA `OCC`.
- [gibMacOS](https://github.com/corpnewt/gibMacOS) Build your own MacOS image.
- [ProperTree](https://github.com/corpnewt/ProperTree) Plist editor.
