<p align="center"><img height="120" align="center" src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fa/Apple_logo_black.svg/1000px-Apple_logo_black.svg.png" alt="logo"/></p>
<h1 align="center">Ryzentosh EFI</h1>
<h1 align="center">All OpenCore 0.5.9 files to boot with a GUI.</h1>
<br>

### What is a Ryzentosh?

**Ryzentosh** is a Hackintosh (macOS on a non Apple computer), with a **AMD Ryzen** processor.

### What is OpenCore?

[**OpenCore**](https://github.com/acidanthera/OpenCorePkg) is a boot loader, this is what allows you to boot with **macOS**.

### How do we configure?

You **must** have [**ProperTree**](https://github.com/corpnewt/ProperTree) and [**Gen-SMBIOS**](https://github.com/corpnewt/GenSMBIOS), you can see [**this video**](https://www.youtube.com/watch?v=8MsueH5EouQ) on **YouTube**.

### Where is the configuration used?

It is launched on a PC with
* Processor: Ryzen **5 3600X** (at 4 Ghz)
* Motherboard: Gigabyte **B450 Aorus Elite** 
* Graphic card: Gigabyte **RX 5600XT (6gb)** Windforce OC
* **16**Gb of RAM with **3200**Mhz
* DD (first): Crucial 2,5 SSD **120**Gb (for macOS)
* DD (second): Crucial M.2 SSD **512**Gb (for Windows)
* DD (third): Western Digital HDD **1**To (for stockage)

### What are the kexts used?

* [**AppleALC**](https://github.com/acidanthera/AppleALC/releases) (for sound)
* [**Lilu**](https://github.com/acidanthera/lilu/releases) (for cpu patches)
* [**Realtek RTL8111**](https://github.com/Mieze/RTL8111_driver_for_OS_X/releases/tag/v2.2.2) (for the Ethernet card)
* [**VirtualSMC**](https://github.com/acidanthera/virtualsmc/releases) (for virtualize SMC information)
* [**WhateverGreen**](whatevergreen) (for other patches)
