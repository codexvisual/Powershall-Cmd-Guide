# # 🚀 Windows Setup & Optimization Guide (Safe & Legal)

Simple guide for Windows setup, optimization, maintenance & useful commands.

No crack ❌ | No bypass ❌ | Only legal tools ✅

---

# 🖥 Setup Commands

## 🔄 Check Windows Version
```powershell
winver
```

## 📦 Update System
```powershell
Settings → Windows Update → Check updates
```

## ⚡ Install Apps (Winget)
```powershell
winget upgrade --all
```

```powershell
winget install Google.Chrome
winget install Mozilla.Firefox
winget install Git.Git
winget install Microsoft.VisualStudioCode
winget install VideoLAN.VLC
winget install 7zip.7zip
winget install Discord.Discord
winget install OBSProject.OBSStudio
```

---

# 🚀 Performance Boost

## 🧹 Cleanup
```powershell
cleanmgr
```

```powershell
del /q/f/s %TEMP%\*
```

## ⚡ Restart Explorer
```powershell
taskkill /f /im explorer.exe & start explorer.exe
```

## 📊 Performance Monitor
```powershell
perfmon
```

## 📌 Task Manager
```powershell
taskmgr
```

---

# 💾 Storage & System

## Check Disk Usage
```powershell
Get-PSDrive
```

## System Info
```powershell
systeminfo
```

## CPU Info
```powershell
wmic cpu get name
```

## RAM Info
```powershell
wmic memorychip get capacity
```

---

# 🌐 Network Commands

## IP Info
```powershell
ipconfig
```

## Flush DNS
```powershell
ipconfig /flushdns
```

## Reset Network
```powershell
netsh winsock reset
```

## Test Connection
```powershell
ping google.com
```

---

# 🔐 Security Commands

## Open Security Center
```powershell
windowsdefender:
```

## Quick Scan
```powershell
Start-MpScan -ScanType QuickScan
```

## Firewall Status
```powershell
netsh advfirewall show allprofiles
```

---

# 🛠 Developer Setup

## Git + VS Code + Node
```powershell
winget install Git.Git
winget install Microsoft.VisualStudioCode
winget install OpenJS.NodeJS
winget install Python.Python.3.12
```

## Check Node Version
```powershell
node -v
npm -v
```

---

# ⚙️ System Tools

## Settings Open
```powershell
start ms-settings:
```

## Control Panel
```powershell
control
```

## Device Manager
```powershell
devmgmt.msc
```

## Services
```powershell
services.msc
```

---

# 🔥 Advanced Commands

## Restart PC
```powershell
shutdown /r /t 0
```

## Shutdown PC
```powershell
shutdown /s /t 0
```

## Log Off
```powershell
shutdown /l
```

## Check Network Config
```powershell
ipconfig /all
```

---

# 📦 Winget Full Package List

```powershell
winget list
```

```powershell
winget search vscode
```

```powershell
winget upgrade --all
```

---

# 🧼 Maintenance Tips (Simple)

- Weekly Windows Update check  
- Temp files cleanup  
- Uninstall unused apps  
- Keep 20% storage free  
- Update drivers regularly  

---

# ⚠ Important Note

এই সব commands Windows official tools ব্যবহার করে safe & legal ভাবে কাজ করে।

❌ No cracking  
❌ No bypass  
✔ Only legit system commands  

---

# 🤝 Contribution

You can:

- Add more useful commands
- Improve optimization tips
- Suggest new tools
- Create Pull Requests

---

Made with ❤️ by CodexVisual
