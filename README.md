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
## 🛡️ Security & False Positives

Some antivirus software (notably **Windows Defender**) may flag this tool as a "False Positive" (e.g., `Trojan:Win32/Wacatac.B!ml`). This is a common occurrence with small, independent C++ utilities.

### 🔍 Why is it flagged?
* **AI-driven Detection (!ml):** The `!ml` tag stands for Machine Learning. It indicates that the antivirus AI is essentially "guessing" based on heuristics. Since this is a compact, newly released binary without a costly Microsoft digital signature, the AI defaults to flagging it as a potential threat.
* **System API Usage:** To function correctly, the tool uses standard Windows APIs that are sometimes mimicked by malware:
    1. **GetPixel:** Used to analyze background brightness so the crosshair can dynamically change color.
    2. **RegisterHotKey:** Used to allow you to reposition the overlay using your arrow keys.
    3. **WS_EX_TOPMOST:** Used to ensure the overlay remains visible over the game window.

### ✅ Verification & Safety
* **VirusTotal Result:** [5/70 Detections (View Full Report)](https://www.virustotal.com/gui/file/afd9a33654320e00eb94ed14f6f6c89fdfae0ea6fd8b7d6b5a9575491911b3c6/details)
* **Status:** **Safe to use.** All major, industry-leading security engines (including **Kaspersky, ESET, and BitDefender**) confirm the file is 100% clean.
* **VAC Status:** This is a standalone overlay. It **does not** inject code into the game, modify game memory, or bypass any anti-cheat systems. It is as safe as using a monitor's built-in crosshair.

---
If you find this tool helpful, please leave a ⭐ to support the project!
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

