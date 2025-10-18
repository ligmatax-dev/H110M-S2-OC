## 🖥️ Hardware & System

| Name | Model Version |
| -------- | ----------------------------- |
| Motherboard | Gigabyte H110M S2-CF |
| BIOS Version | F27b |
| CPU | Intel i3 7100 3.9GHz Kaby Lake |
| Graphics | Intel HD Graphics 630 |
| Sound Card | None |
| Storage | WD Blue 500GB HDD |
| Latest Tested System | macOS Tahoe 26 |
| Bootloader | OpenCore 1.0.6 |
| SMBIOS | iMac18,1 | 

## ✅ Status

| Feature            | Description    | State |
|:-------------------|:---------------|:-----:|
| Booting            |                | ✅    |
| VGA Port           |                | ✅    |
| HDMI Port          |                | ✅    |
| FaceTime           |                | ✅    |
| iGPU QE/CI         |                | ✅    |
| Updates            |                | ✅    |
| iCloud & App Store |                | ✅    |
| Sleep              |                | ✅    |
| Ethernet           |                | ✅    |
| iMessage           |                | ✅    |

## 🍃 Supported macOS Versions
- macOS Sierra 10.12.6
- macOS High Sierra 10.13.x
- macOS Ventura 13.x
- macOS Sonoma 14.x
- macOS Sequoia 15.x
- macOS Tahoe 26.x

## 🍁 BIOS Settings
- M.I.T
  - Advanced Frequency Settings
    - Advanced CPU Core Settings
      - Hypet-Threading Technology : `Enabled`
      - Intel Speed Shift Technology : `Enabled`
- BIOS
  - Fast Boot : `Disabled`
  - OS Type : `Windows 8 / 10`
  - Secure Boot : `Disabled`
- Peripherals
  - Super IO Configuration
    - Serial(COM) Port : `Disabled`
    - Parallel Port : `Disabled`
  - USB Configuration
    - XHCI Hand-Off : `Enabled`
    - Port 60/64 Emulation : `Disabled`
  - SATA And RST Configuration
    - SATA Mode : `AHCI`
- Chipset
  - VT-d : `Disabled`
    - If DisableIoMapper is set to True, VT-d can be set to Enabled.
  - DVMT Pre-Allocated Memory : `64 MB`

VGA Port Patched on config.plist. Now, you do not need to add -igfxvesa on setup.
For FaceTime, iMessage and other iServices, you need to change serial number. Check coverage of your serial number.
