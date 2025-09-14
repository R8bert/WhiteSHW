# 🌟 WhiteSHW Icon Theme

A custom icon theme for Linux desktops, mixing the best bits of WhiteSur, Win10Sur, Sevi, and Hatter icon sets. I built this for fun, focusing on a sleek, unified look rather than perfect app-to-icon matches. It’s all about making your desktop feel modern and stylish.

> **Note:** This is a personal project created for fun and aesthetics. Installing WhiteSHW will overwrite the **WhiteSur** icon theme, so back up your existing themes before proceeding.

---


## 🚀 Installation

Run the installation with a single command:

```bash
./install.sh -a
```

### Available Options

| Option                        | Description                                                                                           |
| :---------------------------- | :---------------------------------------------------------------------------------------------------- |
| `-d`, `--dest`                | Specify theme destination directory (Default: `$HOME/.local/share/icons`)                             |
| `-n`, `--name`                | Specify theme name (Default: `WhiteSur`)                                                              |
| `-t`, `--theme`               | Choose theme color variant(s): `default`, `purple`, `pink`, `red`, `orange`, `yellow`, `green`, `grey`, `all` (Default: `blue`) |
| `-a`, `--alternative`         | Install alternative icons (redesigned versions of default icons)                                      |
| `-b`, `--bold`                | Install bold panel icons for high-resolution displays (recommended for 4K with 200% scale)            |
| `-r`, `--remove`, `-u`, `--uninstall` | Uninstall (remove) icon themes                                                                |
| `-h`, `--help`                | Display help information                                                                             |

### Recommendations

- For a cohesive look, pair WhiteSHW with the **WhiteSur GTK Theme** by vinceliuice: [GitHub Repository](https://github.com/vinceliuice/WhiteSur-gtk-theme).
- ⚠️ **Important:** Installing this theme will overwrite the **WhiteSur icon theme** if it’s already installed. Make sure to back up your existing themes before proceeding!
- **Snaps Note**: To use with snap applications, copy the `.desktop` file from `/var/lib/snapd/desktop/applications/name-of-the-snap-application.desktop` to `$HOME/.local/share/applications/`. Edit the file and update the `Icon=` field to `Icon=name-of-the-icon.svg`.

---

## 🖼️ Preview

![WhiteSHW Preview](https://github.com/user-attachments/assets/657034d8-f9cb-4dd7-afc3-7f161299e112)

---

## 🙌 Credits

WhiteSHW is a fusion of four amazing icon themes, each contributing to its unique style:

- **[WhiteSur Icon Theme](https://github.com/vinceliuice/WhiteSur-icon-theme)**
- **[Win10Sur Icon Theme](https://github.com/yeyushengfan258/Win10Sur-icon-theme)**
- **[Sevi Icon Theme](https://github.com/TaylanTatli/Sevi)**
- **[Hatter Icon Theme](https://github.com/Mibea/Hatter)**

---
