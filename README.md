<a name="readme-top"></a>
<p align=center>
  <img src="https://img.shields.io/badge/warning-system%20modification-critical?style=for-the-badge&color=red" alt="Warning">
</p>
<div align="center">
  <img src="https://github.com/Seph29/Lumos-G1/blob/aade853dda2ed909629fa3b2e7afcab87efb9e8c/docs/logo.png" alt="Lumos G1 Logo"/>
  <br />
  <p><b>Unlock app installation on the INNIOASIS G1 without bootloader unlock</b></p>  <br />
  <p align="center"><img src="https://img.shields.io/github/v/release/Seph29/Lumos-G1?style=for-the-badge" alt="Release"/>
        <img src="https://img.shields.io/github/downloads/Seph29/Lumos-G1/total?label=Downloads&style=for-the-badge" alt="Downloads"/>
        <img src="https://img.shields.io/github/issues/Seph29/Lumos-G1?label=Issues&style=for-the-badge" alt="Issues"/>
        <img src="https://img.shields.io/github/stars/Seph29/Lumos-G1?style=for-the-badge" alt="Stars"></p>
        <a href="https://discord.gg/ttfbVCavBk"><img src="https://img.shields.io/discord/1381673570643742822?label=Discord&logo=discord&style=for-the-badge&color=5865F2" alt="Discord"/></a>

  <br />
</div>

> ⚠️ **WARNING: MAY BRICK YOUR DEVICE**  
> This app modifies critical system partitions on the INNIOASIS G1 (boot and system).  
> Misuse can permanently **brick** your device.  
> The application is still in the beta test phase.  
> ❗ **If you don't understand what this app does or why you need it, do not use it.**

---

## 📖 Overview

**Lumos** is an Android app for the INNIOASIS G1. It unlocks the ability to install applications by patching the system automatically, without unlocking the bootloader.

---

## 🎥 Demo

<div align="center">
  <a href="https://www.youtube.com/watch?v=F3ZEJCmKp9I"><img src="https://img.youtube.com/vi/F3ZEJCmKp9I/0.jpg" alt="Lumos G1 Logo"/></div>

---

## 📷 Screenshots

<p align="center">
  <img src="https://github.com/Seph29/Lumos-G1/blob/main/docs/imgs/alertdialog-EN.png" width="200"/> &nbsp;
  <img src="https://github.com/Seph29/Lumos-G1/blob/main/docs/imgs/screen-EN.png" width="200"/> &nbsp;
</p>

<details>
  <summary>📂 Show more screenshots</summary>
  <br/>

  <p align="center"><b>🌐 Multilingual screens</b></p>
  <p align="center">
    <img src="https://github.com/Seph29/Lumos-G1/blob/main/docs/imgs/screen2-DE.png" width="200"/> &nbsp;
    <img src="https://github.com/Seph29/Lumos-G1/blob/main/docs/imgs/screen2-FR.png" width="200"/> &nbsp;
    <img src="https://github.com/Seph29/Lumos-G1/blob/main/docs/imgs/screen2-EN.png" width="200"/>
  </p>

  <br/>
  <p align="center"><b>🛠 Restore menu</b></p>
  <p align="center">
    <img src="https://github.com/Seph29/Lumos-G1/blob/main/docs/imgs/patched-EN.png" width="200"/> &nbsp;
    <img src="https://github.com/Seph29/Lumos-G1/blob/main/docs/imgs/restore-EN.png" width="200"/>
  </p>
</details>

---

## ⭐️ Features

- No bootloader unlock required  
- Automatic firmware version and language detection *(FR / EN / DE supported)*  
- Preliminary support for legacy firmware formats *(G1-1.24, EN-2.20.x, V2.00.x, etc.)*  
- Two-stage patching: boot partition first, then system (reboot required)  
- Partial restore available: revert only the system (boot remains patched), allowing fast toggle for app installation  
- Integrity check: all critical files are verified using digital signatures  
- Automatic firmware dump upload for unsupported versions  
- Automatic update notification when a new version is available *(includes Changelog button with direct link to release notes)*  
- Battery check: prevents patching or restore if device is not charging or below 20%  
- Backup verification: restoration is only possible if a valid backup is present  
- Multilingual interface (French, English, German)

---

## 📦 Supported Versions

| Language | Expected Version |
|----------|------------------|
| FR       | 3.03.250113      |
| EN       | 2.14.250109      |
| DE       | 2.08.250113      |

**Alternative firmware versions** (not officially supported, but likely to work):

| Language | Expected Version |
|----------|------------------|
| DE       | 2.07.241011      |
| EN       | 2.07.241008      |
| DE       | 3.02.241011      |
| EN       | 2.06.240418      |

> ⚠️ If your firmware version is not listed above, you must update it before using the app.

👉 [Full build compatibility matrix](docs/build-compatibility.md)

---

## ⚙️ Installation

1. Download the latest release from the **Releases** tab or [here](https://github.com/Seph29/Lumos-G1/releases/download/v1.0.10/lumos-v1.0.10.apk)
2. Install the APK on the G1 (via Download, USB, ADB, etc.)  
3. Start the application and click the INJECT button.  
4. After the first restart, start the application a second time and press INJECT again.  
5. Enjoy!

> ⚠️ If your G1 is stuck on the INNIOASIS logo after flashing, you must reflash the correct firmware using SP Flash Tool.
> If you're not familiar with how to use SP Flash Tool, I strongly advise against using this application.

---

## ❓ FAQ

**Is my G1 rooted after installing Lumos ?**  
No. The app uses temporary root access only during the patch process. Your device remains unrooted after reboot.

**Can I completely remove Lumos ?**  
Yes. You need to reflash the original `boot.img` and `system.img` using SP Flash Tool.

**Is it possible to unlock the bootloader ?**  
No. As far as I know, the G1 bootloader cannot be unlocked.

**Does Lumos work on all firmware versions ?**  
No. Only specific versions are officially supported. Others may work, but without guarantee.

**Does Lumos install a custom recovery or modify the bootloader ?**  
No. Lumos does not install a recovery or change the bootloader. However, it replaces the original `boot.img` with a patched version.

**Can I update the firmware after using Lumos ?**  
Not recommended. Updating the firmware will overwrite Lumos patches, and you may need to reapply or adapt it to the new version.

**I've installed this app to my G1 but it doesn't look like yours.**  
It is normal, to have the same style you can install `Nova Launcher`, `Google Keyboard` and `Cx File Explorer`.

---

## 🧰 External Binaries
The app uses `xdelta3` (Apache 2.0 license) and `mtk-su` by [Diplomatic](https://forum.xda-developers.com/member.php?u=8132642).  
These tools are downloaded automatically at runtime.

---

⚠️ Use at your own risk. No warranty is provided.

<p align="right"><a href="#readme-top">Back to top ⬆️</a></p>
