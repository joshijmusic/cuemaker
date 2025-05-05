# 🎛️ CueMaker – Automated Cue Placement for Rekordbox

**CueMaker** automates cue and color placement for Rekordbox tracks with two drops.  
This is a work-in-progress project built with zero coding experience – expect bugs and weirdness.  

---

## ⚠️ Track Requirements

- Must have **2 drops**
- Must have **at least 32 bars before each drop**

> This fits **90%+ of songs**, regardless of BPM.

---

## 🔧 Rekordbox Setup

Before using CueMaker:

1. **Export Mode** – Make sure Rekordbox is in Export Mode  
2. **Beat Jump = 8 Bars** – Set this on the left side of the player  
3. **Quantise = ON** – The red `Q` at the bottom right  
4. Ensure the **BPM and beat grid** are correct and aligned

---

## 🎵 First-Time Setup (Per Track)

### 1. Load the Track
Drag a song into the Rekordbox **Export Player**.

### 2. Set Memory Cues Manually (in Rekordbox)

#### First Drop
- Go to the **first drop**
- Press `C`, then `M` to drop a memory cue
- Press the **left arrow**, then `C`, `M` – **repeat this 4 times**

#### Second Drop
- Go to the **second drop**
- Press `C`, then `M`
- Press the **left arrow**, then `C`, `M` – **repeat this 4 times**

> ✅ You now have **10 memory cues** total (5 per drop)

### 3. Register Cue Locations in CueMaker
- Click **Start** in CueMaker
- For each cue (top to bottom, right panel in Rekordbox), press **Spacebar** to register the location

### 4. Set Cue Colours
Customize colours (e.g., Purple > Blue > Green > Orange > Red)

For each cue:
1. **Right-click** the cue
2. Hover over your desired **color**
3. Press **Spacebar** to save that color location
4. **Left-click** to apply the color

Repeat for all 10 cues

---

## ✅ Automate New Tracks

For any new song:

1. Verify **BPM and beat grid**
2. Add **2 memory cues** (at first and second drop) with `C`, `M`
3. Click **Start Automation** or press **F8** in CueMaker

> 🎉 CueMaker automatically adds all remaining cues and colors using your template

---

## 🛠️ Status

This is an early-stage tool – feel free to fork, contribute, or create issues.  
Made with passion by **Team JOSHIJ 2025**

