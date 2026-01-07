
<div align="center">

#  HyprZepyx Project 

A robust, high-performance Hyprland configuration, focused on workflow efficiency, customization, and a refined visual experience for developers and advanced Linux users.

![](https://img.shields.io/github/last-commit/xZepyx/HyprZepyx?&style=for-the-badge&color=8ad7eb&logo=git&logoColor=D9E0EE&labelColor=1E202B)
![](https://img.shields.io/github/stars/xZepyx/HyprZepyx?style=for-the-badge&logo=andela&color=86dbd7&logoColor=D9E0EE&labelColor=1E202B)
![](https://img.shields.io/github/repo-size/xZepyx/HyprZepyx?color=86dbce&label=SIZE&logo=protondrive&style=for-the-badge&logoColor=D9E0EE&labelColor=1E202B)

[Website](https://zepyx.home.kg/hyprzepyx)

</div>

---

## Overview

**HyprZepyx** delivers a modular, modern Hyprland setup, designed for users prioritizing speed, system clarity, and clean screens. The repository is frequently updated and structured for maintainability and ease of adjustment, supporting multiple color schemes and minimal distractions.

> [!CAUTION]
> * This configuration is not used by me anymore.
> * No support will be provided. (Probably)
> * Have a look at [nucleus-shell](https://github.com/xZepyx/nucleus-shell) (if you want something better)

---

## Features

- Comprehensive Hyprland configuration for advanced users
- Multiple curated visual themes and color schemes
- Adaptive and theme-specific Waybar integration
- Clearly organized configs and modular scripts
- Minimal system overhead, suitable for performance-oriented setups
- Regular updates reflecting current Hyprland standards

---

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/xZepyx/HyprZepyx.git ~/hyprzepyx
    cd ~/hyprzepyx
    ```
2. Install dependencies:
    ```bash
    bash deps-installer.sh
    ```
3. Copy configuration files as required.
4. Launch Hyprland:
    ```bash
    hyprland
    ```

Additional setup guidance can be found in docs or script comments.

---

## Screenshots

### Quiet-Fracture

| Desktop                                          | Launcher                                           |
| ------------------------------------------------ | -------------------------------------------------- |
| ![Widgets](.previews/quiet-fracture/desktop.png) | ![Launcher](.previews/quiet-fracture/launcher.png) |

### Kernel-Fault<sup>ignis</sup>

| Widgets                                        | Launcher                                         |
| ---------------------------------------------- | ------------------------------------------------ |
| ![Widgets](.previews/kernel-fault/widgets.png) | ![Launcher](.previews/kernel-fault/launcher.png) |

Additional previews and themes are available under `.previews/`.

---

## Troubleshooting

- **Waybar icons missing:** Install FontAwesome or Material Icons.
- **Eww widgets don’t appear:** Ensure `eww daemon` is running before launching Hyprland.
- **Rofi launcher errors:** Verify path correctness in `rofi/config.rasi`.
- **Hyprland crash:** Review logs in `~/.local/share/hyprland.log` for diagnostics.

---

## Roadmap

- Transition from Wofi to Walker
- Enhanced wallpaper switcher
- Unified installation script
- Modular dependency management per theme

---

## Maintainer

- **Primary Contact:** xZepyx  
- **Email:** [zepyxunderscore@gmail.com](mailto:zepyxunderscore@gmail.com)

---

_The Spectral-Horizon theme is forked from end4 dotfiles, with modifications for privacy and performance._

---

## License

© 2025–2040 xZepyx (Aditya Yadav)  
Licensed under GNU GPLv3.
