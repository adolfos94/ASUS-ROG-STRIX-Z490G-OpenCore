<center>

# ASUS-ROG-STRIX-Z490G OpenCore EFI

<img src="./Docs/OpenCore_with_text_Small.png"/>

![Static Badge](https://img.shields.io/badge/Apple-gray?style=for-the-badge&logo=apple&logoColor=white)
![Static Badge](https://img.shields.io/badge/ROG-%23FF0029?style=for-the-badge&logo=republic%20of%20gamers&logoColor=white)
![Static Badge](https://img.shields.io/badge/macOS-%23000000?style=for-the-badge&logo=macos&logoColor=white)

</center>

## Software

|     Name      | Version |
| :-----------: | :-----: |
|     macOS     |  13.6   |
|   OpenCore    |  0.9.5  |
|   AppleALC    |  1.8.6  |
|     Lilu      |  1.6.7  |
|    NVMeFix    |  1.1.1  |
|  VirtualSMC   |  1.3.2  |
| WhateverGreen |  1.6.6  |

## Hardware

|   Part    |               Model                |      Comments      |
| :-------: | :--------------------------------: | :----------------: |
|    CPU    |        Intel Core i7-10700         |       Stock        |
|   MOBO    |           ASUS ROG Z490G           |   Wi-Fi Version    |
|    RAM    | CORSAIR - Vengeance RGB PRO 8GB\*4 | OC to 3200 MHz C16 |
|   iGPU    |       Intel UHD Graphics 630       |      Enabled       |
|   dGPU    |          NVIDIA RTX 3800           |      Disabled      |
| Storage 1 |     Seagate FireCuda 510 1 TB      |     Windows HD     |
| Storage 2 |    Seagate FireCuda 120 500 GB     |   Hackintosh HD    |

## Features

|               Function                | Status |             Comments             |
| :-----------------------------------: | :----: | :------------------------------: |
|                  USB                  |   ✅   |     See USB mapping section      |
|               Ethernet                |   ✅   |   Using Apple's I225LM driver    |
|                 Wi-Fi                 |   ❌   |  Need to add Wi-Fi card driver   |
|               Bluetooth               |   ❌   |  Need to add Wi-Fi card driver   |
| AirDrop, Handoff, Universal Clipboard |   ❌   |  Need to add Wi-Fi card driver   |
|         Hardware Acceleration         |   ✅   | Using iGPU Hardware Acceleration |
|                  DRM                  |   ✅   | Using iGPU Hardware Acceleration |
|                 Sleep                 |   ✅   |   Need to use mouse to wake up   |

## Modify config.plist in the OC Folder

This repository contains EFI based on OpenCore 0.9.5. If you're using the same mobo, then this EFI is likely working for you. But if you have different parts other than mobo, please read the following content and modify it accordingly.

- [OpenCore]("https://dortania.github.io/OpenCore-Install-Guide/")

> [!NOTE]
> You need [ProperTree](https://github.com/corpnewt/ProperTree) to open and edit config.plist.
