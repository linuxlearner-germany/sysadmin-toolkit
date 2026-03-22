# 🔁 Ventoy Setup

Ventoy is used as the main bootloader for this toolkit.
It allows booting multiple ISO files directly from a USB drive without extraction.

---

## 🚀 Features

* Boot multiple ISO files from a single USB
* No need to reformat when adding new ISOs
* Supports Windows, Linux, and recovery tools
* Fast and easy to update

---

## 📦 Installation

### 1. Download Ventoy

👉 https://www.ventoy.net/

---

### 2. Install on USB

```bash
sudo ./Ventoy2Disk.sh -i /dev/sdX
```

⚠️ Replace `/dev/sdX` with your USB device
⚠️ This will erase the USB drive

---

### 3. Add ISOs

After installation, simply copy ISO files to the USB:

```bash
/boot/iso/custom/
```

---

## ⚙️ Configuration

Ventoy can be customized using the `ventoy.json` file.

Example:

```json
{
  "theme": {
    "file": "/ventoy/themes/theme.txt"
  }
}
```

---

## 🎨 Themes

Themes can be placed in:

```bash
boot/ventoy/themes/
```

---

## 🧩 Recommended Setup

* Ventoy as bootloader
* MediCat USB as full toolkit
* Hiren’s BootCD as lightweight recovery
* Custom ISOs in `iso/custom/`

---

## 🔄 Updating Ventoy

To update Ventoy without losing data:

```bash
sudo ./Ventoy2Disk.sh -u /dev/sdX
```

---


## 📚 Resources

* Official Website → https://www.ventoy.net/
* GitHub → https://github.com/ventoy/Ventoy

---
