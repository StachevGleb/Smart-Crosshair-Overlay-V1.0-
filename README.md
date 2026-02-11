# 🎯 Smart Crosshair Overlay (V1.0)

A lightweight, performance-focused C++ utility that provides a "Smart" crosshair overlay for Windows. Unlike static overlays, this pointer uses a real-time brightness detection engine to ensure your aim point never camouflages into the background.

---
![SGS_Logo](logo.ico) 
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

## 🛠 Controls & Usage
1.  **Run `Pointer by S.G.S.exe`**: Look for the crosshair icon in your System Tray.
2.  **Right-Click Tray Icon**: 
    * Switch between **Dot** and **Crosshair**.
    * Toggle **Positioning: ON/OFF** to unlock/lock movement.
    * Toggle **Color regime: Magenta/Orange** to change color logic.
3.  **Adjust Position**: Use **Arrow Keys** to move the crosshair pixel-by-pixel.
4.  **Save**: Settings save instantly upon closing or changing modes.

📽️ Video Demonstration
![video](croshair_gif.mp4)
---

## 💻 Technical Details (For Developers/Recruiters)
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
**License:** MIT
---

## 📥 [Download Pointer by S.G.S.exe (Latest Version)](https://github.com/StachevGleb/Smart-Crosshair-Overlay-V1.0-/releases/latest)