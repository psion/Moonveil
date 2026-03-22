<p align="center">
  <a href="https://github.com/notcandy001/Moonveil">
    <img src="https://github.com/notcandy001/Moonveil-asset/blob/main/cover.png" alt="Moonveil" width="100%" />
  </a>
</p>

<h3 align="center">🌙 A quiet, moonlit Hyprland environment</h3>

<p align="center">
  <img src="https://img.shields.io/github/last-commit/notcandy001/moonveil?style=for-the-badge&color=8D748C&logoColor=D9E0EE&labelColor=252733" />
  <img src="https://img.shields.io/github/stars/notcandy001/moonveil?style=for-the-badge&logo=starship&color=AB6C6A&logoColor=D9E0EE&labelColor=252733" />
  <a href="https://github.com/notcandy001/crescentshell/tree/master">
    <img src="https://img.shields.io/badge/shell-CrescentShell-8D748C?style=for-the-badge&logo=gnubash&logoColor=D9E0EE&labelColor=252733" />
  </a>
  <br/>
  <a href="https://github.com/notcandy001/moonveil/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/notcandy001/moonveil?style=for-the-badge&color=A1C999&logo=opensourceinitiative&logoColor=D9E0EE&labelColor=252733" />
  </a>
  <a href="https://github.com/notcandy001/moonveil/issues">
    <img src="https://img.shields.io/github/issues/notcandy001/moonveil?style=for-the-badge&logo=bilibili&color=5E81AC&logoColor=D9E0EE&labelColor=252733" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/notcandy001/my-wal">🖼️ Wallpaper Collection</a> •
  <a href="https://github.com/notcandy001/Moonveil/wiki">📖 Wiki</a> •
  <a href="https://github.com/notcandy001/Moonveil/issues">🐛 Issues</a>
</p>


> [!CAUTION]
> **Matugen is required.** Moonveil relies on dynamic color generation and will not function correctly without it.

-----

## 🌙 What is Moonveil?

Moonveil is a carefully crafted Hyprland dotfiles setup built around a clean, minimal aesthetic. It’s designed to stay out of your way — quiet, elegant, and functional.

At its core is **CrescentShell**, a custom [Quickshell](https://quickshell.outfoxxed.me) configuration that powers the bar, lockscreen, sidebars, notifications, and more — all themed dynamically with Matugen.

-----

## ✨ Features

- 🎨 **Matugen-powered dynamic colors** — everything updates from your wallpaper
- 🔒 **Barcode lockscreen** — unique password visualization inspired by [Rexcrazy804/Zaphkiel](https://github.com/Rexcrazy804/Zaphkiel)
- 🎵 **Cava music visualizer** in the notch — reacts to playing media
- 🖥️ **CrescentShell** — custom Quickshell bar, sidebars, overview, and more
- 💊 **Floating notch** — shows time, active window, media visualizer
- ⚡ **Power profile switcher** — quick dropdown in the bar
- 🌊 **Smooth animations** throughout
- 🧩 **Modular and easy to extend**

-----

## 📸 Screenshots

<div align="center">
  <img src="https://github.com/notcandy001/Moonveil-asset/blob/main/1.png" width="100%" />
  <br/><br/>
  <img src="https://github.com/notcandy001/Moonveil-asset/blob/main/2.png" width="32%" />
  <img src="https://github.com/notcandy001/Moonveil-asset/blob/main/3.png" width="32%" />
  <img src="https://github.com/notcandy001/Moonveil-asset/blob/main/4.png" width="32%" />
  <br/><br/>
  <img src="https://github.com/notcandy001/Moonveil-asset/blob/main/5.png" width="32%" />
  <img src="https://github.com/notcandy001/Moonveil-asset/blob/main/7.png" width="32%" />
  <img src="https://github.com/notcandy001/Moonveil-asset/blob/main/8.png" width="32%" />
</div>

-----

## 🚀 Installation

```bash
curl -L get.roderic.me/moonveil | sh
```

> Manual installation instructions coming soon in the [Wiki](https://github.com/notcandy001/Moonveil/wiki).

-----

## 📦 Dependencies

<details>
<summary>Click to expand</summary>

### Pacman

|Package                  |Purpose                        |
|-------------------------|-------------------------------|
|`hyprland`               |Wayland compositor             |
|`quickshell`             |Shell framework (CrescentShell)|
|`hyprlock`               |Lock screen fallback           |
|`grim`                   |Screenshots                    |
|`nautilus`               |File manager                   |
|`pavucontrol`            |Audio control                  |
|`lxappearance`           |GTK theme manager              |
|`imagemagick`            |Image processing               |
|`cava`                   |Music visualizer               |
|`power-profiles-daemon`  |Power profile switching        |
|`gnome-bluetooth-3.0`    |Bluetooth support              |
|`python` + `python-*`    |Matugen scripts                |
|`ttf-libre-barcode`      |Barcode lockscreen font        |
|`JetBrainsMono Nerd Font`|Terminal font                  |
|`Noto Fonts Emoji`       |Emoji support                  |

### AUR (via yay)

|Package              |Purpose                                |
|---------------------|---------------------------------------|
|`matugen`            |Dynamic color generation (**required**)|
|`adw-gtk-theme`      |GTK theme                              |
|`bibata-cursor-theme`|Cursor theme                           |
|`ttf-geist-mono`     |UI font                                |
|`ttf-pp-neue-machina`|Display font                           |


> Run `fc-cache -fv` after installing fonts.

</details>

-----

## ⌨️ Keybinds

|Key                     |Action                       |
|------------------------|-----------------------------|
|`Super + A`             |Control center (left sidebar)|
|`Super + N`             |Notifications (right sidebar)|
|`Super + Tab`           |Workspace overview           |
|`Super + R`             |App launcher / search        |
|`Super + L`             |Lock screen                  |
|`Super + I`             |Settings                     |
|`Super + /`             |Cheatsheet                   |
|`Super + Shift + Escape`|Power menu                   |
|`Super + Shift + S`     |Region screenshot            |
|`Super + Return`        |Terminal (kitty)             |
|`Super + Q`             |Close window                 |
|`Super + E`             |File manager                 |
|`Super + B`             |Browser                      |

-----

## 🗺️ Roadmap

- [x] Hyprland setup
- [x] CrescentShell (Quickshell bar + sidebars)
- [x] Matugen dynamic colors
- [x] Barcode lockscreen
- [x] Cava music visualizer in notch
- [x] Power profile switcher
- [x] Notification center
- [x] App launcher / overview
- [x] Wallpaper switcher
- [ ] Clipboard manager
- [ ] Emoji picker
- [ ] Dashboard widget
- [ ] Documentation / Wiki
- [ ] Additional color schemes

-----

## 💙 Credits

Moonveil is built on the shoulders of some incredible work:

- **[end-4](https://github.com/end-4/dots-hyprland)** — For his awesome works and  I learned a lot from it. (And yoinked a lot of code and GUI, too for quickshell only. 😅)
- **[Hyprland Community](https://github.com/hyprwm)** — For an outstanding Wayland compositor.
- **[Quickshell](https://quickshell.outfoxxed.me)** — The shell framework powering CrescentShell.

-----

<p align="center">
  Made with 🌙 by <a href="https://github.com/notcandy001">notcandy001</a>
</p>
