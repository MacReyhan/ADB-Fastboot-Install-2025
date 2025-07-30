
# ✅ ADB & Fastboot Auto Installer (with USB Drivers)

This batch script automates:

- Downloading & extracting the latest **ADB + Fastboot (Platform-Tools)**
- Adding ADB to your **system PATH**
- Downloading & installing **Google USB Drivers**

---

## 📥 How to Use

### Step 1: Download & Move Folder
- Download this repository as a ZIP  
- Extract it and move the folder to:  
```

C:\ADB-Auto-Installer\

```

### Step 2: Run the Script
- Right-click `install_adb_fastboot.bat`  
- Select **“Run as Administrator”**

> ⚠️ Make sure you’re connected to the internet while running the script.

---

## 📁 Folder Structure After Running

```

C:
└── ADB-Auto-Installer
├── install\_adb\_fastboot.bat
├── platform-tools
└── usb\_driver\

```

---

## ✅ What It Does

- Installs **ADB & Fastboot** to `platform-tools\`
- Adds ADB to your Windows **system environment PATH**
- Installs **Google USB Drivers** using `pnputil`

---

## 🔁 After Installation

- Open **Command Prompt** and run `adb` from anywhere
- Reconnect your Android device or reboot if not detected

---

## 💡 Compatible With

- Windows 10 & 11  
- All Android devices with USB debugging enabled

---

## ❤️ Credit

Made with 💻 by MacReyhan
