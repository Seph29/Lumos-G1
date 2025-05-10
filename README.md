# Lumos G1

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

Other firmware versions are not officially supported.

---

## Installation

1. Download the latest release from the **Releases** tab (soon)
2. Install the APK on the G1 (via ADB, etc.)
3. Launch the app and follow the on-screen instructions

---

## External Binaries

The app uses `xdelta3` (Apache 2.0 license) and `mtk-su` by [Diplomatic](https://forum.xda-developers.com/member.php?u=8132642).  
These tools are downloaded automatically at runtime.

---

⚠️ Use at your own risk. No warranty is provided.
