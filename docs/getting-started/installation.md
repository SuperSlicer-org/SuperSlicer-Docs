---
title: Installation
description: SuperSlicer installation steps and system requirements
hide:
  #- navigation
  - toc.integrate
  - path
---

# Installation

Below we will go over how to obtain and install SuperSlicer on your system.

---

## Obtaining SuperSlicer

Superslicer releases can be found on the [Releases](../releases.md) page or on the [SuperSlicer Github Releases](https://github.com/supermerill/SuperSlicer/releases) page.

!!! warning

    We only support the current Stable release, and the current development release listed on the [Releases](../releases.md) page. Nightly builds are **NOT** supported!!

---

## System Requirements

!!! info "Windows - Minimum System Requirements"

    - Operating System: Windows 7 64-Bit Version or Later
    - Processor: Intel Core i3 or equivalent
    - Memory: Minimum 4 GB RAM / Recommended 8 GB or More
    - Graphics: DirectX 11 compatible
    - Storage: 500 MB available space

!!! info "Linux - Minimum System Requirements"

    - Processor: Intel Core i3 or equivalent
    - Memory: Minimum 4 GB RAM / Recommended 8 GB or More
    - Graphics: OpenGL 3.2 compatible
    - Storage: 500 MB available space

!!! info "Mac - Minimum System Requirements"

    - Operating System:  OSX 10.12 (Sierra) or Later
    - Processor: Intel Core i3 or equivalent
    - Memory: Minimum 4 GB RAM / Recommended 8 GB or More
    - Graphics: Metal compatible GPU
    - Storage: 500 MB available space

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
