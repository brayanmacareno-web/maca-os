# MACA OS

**MACA OS** is a custom, lightweight Linux distribution built on top of **Arch Linux**. Designed for speed, keyboard-driven productivity, and a clean dark aesthetic, it pairs **i3wm** with custom interactive **EWW** widgets, **Picom** transparency, and a **Calamares** graphical installer.

### Key Highlights
- **Window Manager & Compositor:** `i3-gaps` paired with `Picom` (rounded corners and smooth fading) and `Rofi`.
- **Custom UI:** Interactive top bar, control center, audio visualizer (`cava`), and OSD notifications powered by `EWW`.
- **Ready to Install:** Bootable ISO profile built with `mkarchiso`, custom `SDDM` login screen, and `Calamares` installer.

## Installation

Boot into the **MACA OS** live environment, open a terminal, and run the following commands to connect to Wi-Fi (replacing `wifiname` with your SSID), verify your connection, and launch the installer  (the third command is for a wifi test):

```bash
iwctl
 station wlan0 connect wifiname
ping -c 3 archlinux.org
sudo instalar-maca-os
```
## Download

- **MACA OS (`v1.0-alpha`):** [Download ISO from Google Drive](https://drive.google.com/drive/folders/1XiyYzSO0YpAVDmzbgfZJVOIskjA0Oxr4?usp=sharing)

> **Note:** Because the ISO image is larger than 100 MB, Google Drive will show a virus-scan warning screen. Click **Download anyway** to proceed.

## commands

- **HELP: if you fell lost you can press **win + f1** for commands helps
