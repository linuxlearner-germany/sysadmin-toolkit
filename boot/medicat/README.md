# 🧰 MediCat USB

MediCat USB is an all-in-one bootable toolkit designed for system repair, diagnostics, and data recovery.

It provides a complete portable environment with a wide range of utilities.

---

## 🚀 Features

* Windows-based recovery environment (WinPE)
* Large collection of repair & diagnostic tools
* Disk management & recovery utilities
* Malware removal tools
* Portable applications

---

## 🔁 Ventoy Integration

MediCat uses **Ventoy internally** as its bootloader.

This means:

* No separate Ventoy installation is required
* You can boot MediCat directly
* This repository also supports a standalone Ventoy setup for custom ISOs

---

## 📦 Contents

MediCat typically includes:

* 🛠️ System repair tools
* 💾 Disk & partition utilities
* 🔒 Antivirus & malware scanners
* 🔁 Backup & recovery tools
* 🧪 Diagnostic tools

---

## 💾 USB Drive Requirements

### 📏 Recommended Size

* **Minimum:** 32GB (limited setup)
* **Recommended:** 64GB
* **Optimal:** 128GB+

---

### 📦 Storage Usage

* MediCat → ~20–30GB
* Additional ISOs → optional

---

### ⚡ Performance

* Use **USB 3.0 or higher**
* Prefer reliable brands (SanDisk, Samsung, Kingston)
* Avoid slow drives

---

## ➕ Custom ISO Support

This repository provides a dedicated location for your own ISO files:

```bash
boot/iso/custom/
```

You can add:

* Windows installers
* Linux distributions
* Recovery tools
* Security / pentesting systems

### 💡 Example

```bash
boot/iso/custom/windows10.iso
boot/iso/custom/ubuntu.iso
boot/iso/custom/kali.iso
```

These ISOs can be used alongside MediCat when using a standalone Ventoy setup.

---

## ⚙️ Setup

### 1. Download MediCat

👉 https://medicatusb.com/

---

### 2. Add to USB

* Use the official MediCat installer
* OR copy files to a Ventoy USB

---

### 3. Boot

* Insert USB
* Boot from USB
* Select MediCat

---

## ⚠️ Notes

* MediCat is a large toolkit (~20GB+)
* Some tools may require internet access
* First boot may take longer

---

## ⚠️ Disclaimer

This repository does NOT host MediCat files.
Please respect the licenses of included third-party tools.

---

## 📚 Resources

* Website → https://medicatusb.com/
* Community → https://gbatemp.net/threads/medicat-dvd-a-multiboot-linux-dvd.361577/

---
