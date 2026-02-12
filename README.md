# ![SGS_Logo](logo.ico)  Smart Crosshair Overlay (V1.0)  

A lightweight, performance-focused C++ utility that provides a "Smart" crosshair overlay for Windows. Unlike static overlays, this pointer uses a real-time brightness detection engine to ensure your aim point never camouflages into the background.

---
![gif](https://github.com/user-attachments/assets/2dc99a72-b458-4df4-a562-c8684491c1ff)

****

## 🚀 The Problem & The Solution
Most gaming overlays are static. When you move from a dark cave to a bright snowy field, you lose your crosshair. 

**(Smart Gaming System)** solves this by:
1. **Scanning** the screen pixels directly behind the crosshair.
2. **Calculating** the average brightness.
3. **Switching** colors instantly (e.g., Magenta or Orange for dark areas, Dark Blue for bright areas) to maintain maximum contrast.

---

## ✨ Key Features
* **Dual Modes:** Toggle between a **High-Visibility Dot** and a **T-Shape Crosshair**.
* **Intelligent Contrast Engine:** Automatic color switching based on background luminosity.
* **Zero-Lag Performance:** Written in raw **Win32 C++**. No Electron, no Overwolf, no bloat.
* **Position Lock:** Use Arrow Keys to calibrate, then lock the position to prevent accidental shifts.
* **Persistent Config:** Saves your custom coordinates and preferences to `config.txt` automatically.
* **Stealth Execution:** No "hooks" into game memory—making it a safe, external visual aid.

---

## IMPORTANT: For CS2 and other Source 2 games, you MUST use "Windowed Borderless" mode in Video Settings. The overlay will not show in "Full Screen".

****

## 🛠 Controls & Usage
1.  **Run `Pointer by S.G.S.exe`**: Look for the crosshair icon in your System Tray.
2.  **Right-Click Tray Icon**: 
    * Switch between **Dot** and **Crosshair**.
    * Toggle **Positioning: ON/OFF** to unlock/lock movement.
    * Toggle **Color regime: Magenta/Orange** to change color logic.
3.  **Adjust Position**: Use **Arrow Keys** to move the crosshair pixel-by-pixel.
4.  **Save**: Settings save instantly upon closing or changing modes.

📽️ Video Demonstration


https://github.com/user-attachments/assets/05bae6ef-ee46-498b-8e6c-61ea6749d30c


---

## 💻 Technical Details (For Developers)
This project demonstrates advanced use of the **Windows API**:
* **Custom drawing**: Flicker-free overlays.
* **System Hooks**: Implementing global hotkeys for positioning.
* **Resource Scripting**: Embedding custom `.ico` assets directly into the Windows tray.
* **File I/O**: Efficient state management via local configuration files.

---

## 📥 Installation
1.  Download `Pointer by S.G.S.exe`.
2.  Run and enjoy. No installation required!

---

## 🗺 Roadmap (Thinking to add)
- [ ] Transparency/Alpha-blending slider.
- [ ] More types of crosshairs.
- [ ] Multi-monitor support.


---
**Author:** [Stachev Gleb /  https://github.com/StachevGleb]  

---
⚠️ Note on Antivirus: Because this tool is not digitally signed and performs screen overlays, some browsers/antiviruses may flag it as a "False Positive". This is a common issue with small C++ utilities. You can run it in a sandbox.
---

## 🛡️ Security Report
Because this tool is an unsigned .exe that captures screen pixels for the smart contrast logic, some engines may flag it.
---


* **VirusTotal Result:** [5/70 Detection (False Positive)](https://www.virustotal.com/gui/file/afd9a33654320e00eb94ed14f6f6c89fdfae0ea6fd8b7d6b5a9575491911b3c6/details)
* **Status:** Safe to use. Most major engines (Microsoft, Kaspersky, ESET) show the file is clean.
---
If you find this tool helpful, please leave a ⭐ to support the project!"
---

### 📥 Download
To avoid browser false-positives, the executable is provided inside a ZIP and RAR archives.
* **[Download Smart Crosshair Overlay (RAR)](https://github.com/StachevGleb/Smart-Crosshair-Overlay-V1.0-/blob/master/Pointer%20by%20S.G.S.rar)**
* **[Download Smart Crosshair Overlay (ZIP)](https://github.com/StachevGleb/Smart-Crosshair-Overlay-V1.0-/blob/master/Pointer%20by%20S.G.S.zip)**
---

## 📥 [Download Pointer by S.G.S.exe (Latest Version)](https://github.com/StachevGleb/Smart-Crosshair-Overlay-V1.0-/releases/latest)

---

**Enjoying this project?** Help me keep it updated by [supporting me on Buy Me a Coffee](https://www.buymeacoffee.com/StachevGleb). Cheers! ☕

