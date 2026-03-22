# .xlcore — FFXIV Config Backup (XIVLauncher / Linux)

This repository contains a minimal, version-controlled backup of my FINAL FANTASY XIV configuration when using XIVLauncher on Linux.

## 🔗 Repository

git@github.com:Querzion/.xlcore.git

---

## 📁 Scope

Only essential configuration files are tracked.

### Global Settings
- ffxivConfig/FFXIV.cfg  
  System settings (graphics, sound, etc.)

### Character Settings
- ffxivConfig/FFXIV_CHR*/  
  - HOTBAR.DAT → hotbars / spell layout  
  - KEYBIND.DAT → keybindings  
  - GEARSET.DAT → gear sets  
  - ADDON.DAT → UI / HUD layout  
  - Macros and other per-character data  

---

## ❌ Excluded

This repository intentionally excludes:

- Account data (accounts.json)
- Dalamud (plugins, cache, runtime)
- Logs and temp files
- Wine/Proton prefixes
- Game installation files
- Screenshots

---

## 🧠 Philosophy

This is a dotfiles-style repo, not a full backup.

**Goal:**  
Recreate UI + gameplay configuration instantly on any machine.

---

## 🚀 Setup

### Option 1 — Fresh Machine (Recommended)

```bash
cd ~
git clone git@github.com:Querzion/.xlcore.git .xlcore
