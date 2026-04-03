# 🚀 **Shxdow Cleanup v3.3.1**

[![Version](https://img.shields.io/badge/version-3.3.1-blue.svg)](https://github.com/Shxdow2/Shxdow-Cleanup/releases)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011-lightgrey.svg)](https://www.microsoft.com/windows)

**Shxdow Cleanup** est un outil de maintenance avancé conçu pour optimiser les performances de votre système, libérer de l'espace disque et réduire la latence pour le gaming.

---

## ✨ **Main Features**

* 🌍 **Multi-Language Support:** Full **English** and **French** support with automatic configuration saving.
* ⚡ **Deep Gaming Optimization:** Disables **VBS**, flushes **RAM** via native C# API, and clears **DNS/ARP** caches.
* 💾 **Hardware Care:** Native **SSD ReTrim** and automatic removal of **Ghost Devices** (PnP).
* 🧹 **Complete Cleaning:** Deep cleans **Chrome, Edge, Brave, and Opera GX** plus all system temporary files.
* 🛡️ **Safe & Reliable:** Automatic Windows version check and real-time **Logging** of all actions.

---

## 📥 **Installation & Usage**

1. Go to the [**Releases**](https://github.com/Shxdow2/Shxdow-Cleanup/releases) page.
2. Download the **`Cleanup-Shxdow.7z`** archive.
3. Extract the folder to your computer.
4. Right-click **`Shxdow-Cleanup-Launcher.bat`** and select **Run as Administrator**.

> [!IMPORTANT]
> **Windows 10 or 11** is required. The script will automatically create a **`config.json`** file on first launch to save your language preference.

---

## 📊 **What's New in v3.3.1?**

* Added **Internationalization** (Switch between FR/EN).
* New **Hardware Optimization** module (SSD & PnP).
* Improved **RAM Management** for smoother multitasking.
* Enhanced **Browser Support** for modern web cleaners.

---

## 🛠 **Configuration**

The script uses a **`config.json`** file to store your settings:
```json
{
    "language": "EN",
    "backupDir": "C:\\RegistryBackups",
    "enableLogging": true
}
