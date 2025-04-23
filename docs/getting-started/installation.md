# Installation

This document provides download links for obtaining binaries for SuperSlicer and instructions for getting it installed on your system.

---
## System Requirements

##### Windows – Minimum System Requirements:

- Operating System: Windows 7 64-Bit Version or Later
- Processor: Intel Core i3 or equivalent
- Memory: Minimum 4 GB RAM / Recommended 8 GB or More
- Graphics: DirectX 11 compatible
- Storage: 500 MB available space

##### Linux – Minimum System Requirements:

- Processor: Intel Core i3 or equivalent
- Memory: Minimum 4 GB RAM / Recommended 8 GB or More
- Graphics: OpenGL 3.2 compatible
- Storage: 500 MB available space

##### Mac – Minimum System Requirements:

- Operating System:  OSX 10.12 (Sierra) or Later
- Processor: Intel Core i3 or equivalent
- Memory: Minimum 4 GB RAM / Recommended 8 GB or More
- Graphics: Metal compatible GPU
- Storage: 500 MB available space

---

## Obtaining SuperSlicer

Download links are below for the latest Stable and Development versions of SuperSlicer.

Other releases can be found on the [SuperSlicer Github Releases](https://github.com/supermerill/SuperSlicer/releases) page

[Nightly Builds](https://github.com/supermerill/SuperSlicer/actions?query=branch%3Anightly_dev) builds can be found on github actions under the nightly_dev branch

---

#### Stable Release (2.5.59.13)

[Windows](https://github.com/supermerill/SuperSlicer/releases/download/2.5.59.13/SuperSlicer_2.5.59.13_win64_240701.zip)
SHA256 Checksum: `aefc6d051b3b3e6e1d1a571d66cb267a09d7cfbe2d8f889a433cd8ac5f787a69`

[Mac Intel](https://github.com/supermerill/SuperSlicer/releases/download/2.5.59.13/SuperSlicer_2.5.59.13_macos_240701.dmg)
SHA256 Checksum: `37ead99e2bbce30cdf411b50dc9cf41f70acaa8e9f8371ed5b8f5c7ad43b3a13`

[Mac Arm](https://github.com/supermerill/SuperSlicer/releases/download/2.5.59.13/SuperSlicer_2.5.59.13_macos_arm_240701.dmg)
SHA256 Checksum: `5e1358d36c4948177aca4caaccea9532cf357517ec9464284d9126f0a65677bb`

[Linux](https://github.com/supermerill/SuperSlicer/releases/download/2.5.59.13/SuperSlicer_2.5.59.13_linux64_240701.tar.zip)
SHA256 Checksum: `6f5588b0467ed00eab6a1ad70d52f075ee65f862a455efcfc214f3e2c7781e1c`

[Linux AppImage](https://github.com/supermerill/SuperSlicer/releases/download/2.5.59.13/SuperSlicer-ubuntu_20.04-2.5.59.13.AppImage)
SHA256 Checksum: `332dfbb7046fc12c1936900be2a85ce0f13031b381edf266f8c6d08d94730da4`

#### Latest Development Release (2.7.61.0 Beta)

[Windows](https://github.com/supermerill/SuperSlicer/releases/download/2.7.61.0/SuperSlicer_2.7.61.0_win64_250325.zip)
SHA256 Checksum: `085513e119d26f18486247729bbdf346b1929b0feb9c44cafaad3d15b3e888fa`

[Mac Intel](https://github.com/supermerill/SuperSlicer/releases/download/2.7.61.0/SuperSlicer_2.7.61.0_macos_intel_250325.dmg)
Currently Broken

[Mac Arm](https://github.com/supermerill/SuperSlicer/releases/download/2.7.61.0/SuperSlicer_2.7.61.0_macos_arm_250325.dmg)
SHA256 Checksum: `3f47a518063455dae861ac84e031667fb5d33ef1b50da2d7ac446653fce9114e`

[Linux AppImage](https://github.com/supermerill/SuperSlicer/releases/download/2.7.61.0/SuperSlicer-ubuntu_22.04-gtk3-2.7.61.0.AppImage)
SHA256 Checksum: `03f5640135bdbdccc107399ae776247366838f8835b6a2a15065467b290e1c01`

---

## Installation Steps

### Windows
 - Download the zip file
 - Create a Directory in `C:\Program Files\SuperSlicer\`
 - Extract the zip file to this directory

### Mac
 - Download the DMG file and double click it
 - Drag and Drop the SuperSlicer.app to the Applications directory
 - Open a terminal and then run `xattr -d com.apple.quarantine /Applications/SuperSlicer.app` Note: This is currently required to work around SuperSlicer not being signed by Apple.
 - Double click on the SuperSlicer.app file to open SuperSlicer
 

### Linux
 - Download the AppImage file
 - Place the AppImage file where you would like to run it from
 - Double Click the AppImage to open SuperSlicer

