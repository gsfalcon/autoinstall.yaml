This repository contains an **automated installation script** (`autoinstall.yaml`) for Ubuntu, designed to streamline system setup with pre-configured packages, drivers, and system tweaks.

## Features 🔧
- **Minimal Ubuntu Desktop Installation**
- **Pre-installed essential applications** (Git, VLC, GIMP, Kdenlive, OBS Studio, etc.)
- **Pre-configured AMD drivers** (for B350 chipset and RX 580 GPU)
- **GNOME customizations** (GNOME Tweaks, Dash to Panel)
- **Plex Media Server auto-setup**
- **Snap applications included** (Steam, Discord, Plex Media Server)
- **Optimized APT sources & PPAs**

## Installation 💿
1. Boot into the Ubuntu installer.
2. Select **Autoinstall** and provide the following URL:
   ```
   https://gsfalcon.github.io/Ubuntu/autoinstall.yaml
   ```
3. The installation will begin automatically!

## Repository Structure 📂
```
Ubuntu/
├── autoinstall.yaml   # Auto-install configuration
├── README.md          # This file
```

## Notes 📌
- Ensure your network connection is active during installation.
- You may need to adjust BIOS settings for proper booting.
- If the raw GitHub URL does not work, consider hosting on GitHub Pages.

---
