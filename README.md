# Vanigan POS — Official Releases

[![Latest Release](https://img.shields.io/github/v/release/kannansrepos/vanigan-releases?color=blue&label=Latest%20Release)](https://github.com/kannansrepos/vanigan-releases/releases/latest)
[![Platform](https://img.shields.io/badge/Platform-Windows%20x64-brightgreen.svg)](https://github.com/kannansrepos/vanigan-releases/releases/latest)
[![License](https://img.shields.io/badge/License-Proprietary-orange.svg)](https://products.uttech.in)
[![Support](https://img.shields.io/badge/Support-support%40uttech.in-blue)](mailto:support@uttech.in)

Welcome to the official public distribution repository for **Vanigan POS** (by U & T Technologies).  
Download the latest verified desktop client binaries below.

---

## 📥 Downloads (Latest: v1.0.0)

| Package Type | File | Description | Download Link |
| :--- | :--- | :--- | :--- |
| **⚡ Web Installer** *(Recommended)* | `VaniganPOS-WebInstaller.exe` | **Tiny stub (~277 KB)**. Downloads and configures the latest production release on demand. | [Download Web Installer](https://github.com/kannansrepos/vanigan-releases/releases/download/v1.0.0/VaniganPOS-WebInstaller.exe) |
| **💿 Full Offline Setup** | `Vanigan.POS-Setup-1.0.0.exe` | **Full standalone bundle (~88 MB)**. For offline installations without requiring an active internet connection. | [Download Standalone .exe](https://github.com/kannansrepos/vanigan-releases/releases/download/v1.0.0/Vanigan.POS-Setup-1.0.0.exe) |
| **🏢 Enterprise MSI Package** | `Vanigan.POS-Setup-1.0.0.msi` | **Windows Installer (~96 MB)**. Designed for IT administrators, Active Directory GPO, and silent network deployments. | [Download Enterprise .msi](https://github.com/kannansrepos/vanigan-releases/releases/download/v1.0.0/Vanigan.POS-Setup-1.0.0.msi) |

*(Direct release assets can also be browsed on the [GitHub Releases Page](https://github.com/kannansrepos/vanigan-releases/releases/tag/v1.0.0)).*

---

## 💻 System Requirements

* **Operating System:** Windows 10 or Windows 11 (64-bit)
* **Processor:** 1.6 GHz Intel / AMD Dual Core or higher
* **Memory (RAM):** 4 GB minimum (8 GB recommended for heavy supermarket inventories)
* **Storage:** 500 MB free hard disk space
* **Display:** 1280 × 720 resolution or higher

---

## 🚀 Installation Instructions

### Option 1: Web Installer
1. Download `VaniganPOS-WebInstaller.exe`.
2. Double-click the file to run.
3. The installer automatically downloads the latest application packages and sets up your desktop shortcuts.

### Option 2: Full Standalone Setup (.exe)
1. Download `Vanigan.POS-Setup-1.0.0.exe`.
2. Run the executable and follow the setup wizard instructions.

### Option 3: Enterprise Silent Installation (.msi)
For IT managers installing across multiple domain machines via command line or PowerShell:

```powershell
# Silent install with standard log
msiexec /i "Vanigan.POS-Setup-1.0.0.msi" /qn /norestart /l*v "install.log"
```

---

## 🔑 License Activation & Support

Vanigan POS requires a valid license key or evaluation subscription for production billing.

* **License Portal:** [https://products.uttech.in](https://products.uttech.in)
* **Official Website:** [https://www.uttech.in](https://www.uttech.in)
* **Priority Helpline:** +91 9363 6633 50
* **Technical Support:** [support@uttech.in](mailto:support@uttech.in)

---

&copy; 2026 U & T Technologies. All rights reserved.
