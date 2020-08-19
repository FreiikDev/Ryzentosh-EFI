<p align="center"><img height="120" align="center" src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fa/Apple_logo_black.svg/1000px-Apple_logo_black.svg.png" alt="logo"/></p>
<h1 align="center">Ryzentosh EFI</h1>
<h1 align="center">OpenCore 0.5.9 files to boot with the GUI.</h1>
<br>

### What is a Ryzentosh?

**Ryzentosh** is a Hackintosh, with a **AMD Ryzen** processor.

### What is OpenCore?

[**OpenCore**](https://github.com/acidanthera/OpenCorePkg) is a boot loader, this is the part that allows you to boot **macOS** on a non-Apple computer.

### How do I configure?

You **must** have [**ProperTree**](https://github.com/corpnewt/ProperTree) and [**Gen-SMBIOS**](https://github.com/corpnewt/GenSMBIOS).
You can watch [**this video**](https://www.youtube.com/watch?v=8MsueH5EouQ) for more info.

### What's the recommanded config for the configuration

* Processor: Ryzen **5 3600X** (up to 4Ghz)
* Motherboard: Gigabyte **B450 Aorus Elite** 
* Graphic card: Gigabyte **RX 5600XT (6gb)** Windforce OC
* **16**Gb of RAM (**3200**Mhz)
* Crucial 2,5 SSD **120**Gb (for macOS)
* Crucial M.2 SSD **512**Gb (for Windows)
* Western Digital HDD **1**To (for other DATA)

### What are the kexts used for?

* [**AppleALC**](https://github.com/acidanthera/AppleALC/releases) (for sound stuff)
* [**Lilu**](https://github.com/acidanthera/lilu/releases) (for cpu patches)
* [**Realtek RTL8111**](https://github.com/Mieze/RTL8111_driver_for_OS_X/releases/tag/v2.2.2) (for ethernet stuff)
* [**VirtualSMC**](https://github.com/acidanthera/virtualsmc/releases) (for the SMC information virtualization)
* [**WhateverGreen**](whatevergreen) (for some other stuff)
