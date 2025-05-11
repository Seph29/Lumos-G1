# Lumos G1
![Logo](https://github.com/Seph29/Lumos-G1/blob/aade853dda2ed909629fa3b2e7afcab87efb9e8c/docs/logo.png)

![Warning](https://img.shields.io/badge/warning-system%20modification-critical?style=for-the-badge&color=red)

> ⚠️ **WARNING: MAY BRICK YOUR DEVICE**  
> This app modifies critical system partitions on the INNIOASIS G1 (boot and system).  
> Misuse can permanently **brick** your device.
> The application is still in the beta test phase
>
> ❗ **If you don't understand what this app does or why you need it, do not use it.**

---

## Overview

**Lumos** is an Android app for the INNIOASIS G1. It unlocks the ability to install applications by patching the system automatically, without unlocking the bootloader.

---

## 🎥 Demo

[![Watch the video](https://img.youtube.com/vi/F3ZEJCmKp9I/0.jpg)](https://www.youtube.com/watch?v=F3ZEJCmKp9I)

---

## 📷 Screenshot

<img src="https://github.com/Seph29/Lumos-G1/blob/aade853dda2ed909629fa3b2e7afcab87efb9e8c/docs/lumos.png" alt="Screen" width="240" height="400">

---
## Features

- Automatic detection of device language and firmware version
- Two-stage patching: boot partition first, then system (requires reboot)
- Backs up the original file before replacing it (no restore yet)

---

## Supported Versions

| Language | Expected Version |
|----------|------------------|
| FR       | 3.03.250113      |
| EN       | 2.14.250109      |
| DE       | 2.08.250113      |

Other firmware versions are not officially supported but probably works.

| Language | Expected Version |
|----------|------------------|
| DE       | 2.07.241011      |
| EN       | 2.07.241008      |
| DE       | 3.02.241011      |

---

## Installation

1. Download the latest release from the **Releases** tab or [here](https://github.com/Seph29/Lumos-G1/releases/download/v1.0.5/lumos-v1.0.5.apk)
2. Install the APK on the G1 (via Download, USB, ADB, etc.)
3. Start the application and click the INJECT button. After the first restart, start the application a second time and press INJECT again.
4. Enjoy !

> ⚠️ If your G1 is still stuck on the INNIOASIS logo, it is recommended to download the latest firmware from the official INNIOASIS website and flash it using SP Flash Tool.
> If you're not familiar with how to use SP Flash Tool, I strongly advise against using this application.
---

## External Binaries

The app uses `xdelta3` (Apache 2.0 license) and `mtk-su` by [Diplomatic](https://forum.xda-developers.com/member.php?u=8132642).  
These tools are downloaded automatically at runtime.

---

⚠️ Use at your own risk. No warranty is provided.
