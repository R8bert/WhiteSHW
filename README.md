# WhiteSHW Icon Theme

A unique icon theme for Linux desktops, blending the aesthetics of WhiteSur, Win10Sur, Sevi, and Hatter icon sets into a personal project. This theme is designed with a focus on visual appeal, prioritizing a cohesive and stylish look over strict app-to-icon accuracy. Some icons may not directly correspond to their associated applications, but they are crafted to enhance the overall desktop experience with a polished, modern vibe.

**Note:** This is a personal project created for fun and aesthetics. If you install this theme, it will overwrite the WhiteSur icon theme, so proceed with caution if you are using or plan to use WhiteSur.

---

## Installation Instructions

Usage: `./install.sh` **[OPTIONS...]**

| OPTIONS:                      | Description                                                                                           |
| :---------------------------- | :---------------------------------------------------------------------------------------------------- |
| -d, --dest                    | Specify theme destination directory (Default: `$HOME/.local/share/icons`)                             |
| -n, --name                    | Specify theme name (Default: WinSevHat)                                                               |
| -t, --theme                   | Specify theme color variant(s) [default/purple/pink/red/orange/yellow/green/grey/all] (Default: blue) |
| -a, --alternative             | Install alternative icons (redesigned versions of default icons)                                      |
| -b, --bold                    | Install bold panel icons version (recommended for high-resolution displays like 4K with 200% scale)   |
| -r, --remove, -u, --uninstall | Uninstall (remove) icon themes                                                                        |
| -h, --help                    | Show this help                                                                                        |

> **Recommendation:** I recommend downloading vinceliuice's WhiteSur GTK theme for a more complete desktop experience. [https://github.com/vinceliuice/WhiteSur-gtk-theme](#)

> **Important Note:** Installing this theme will overwrite the WhiteSur icon theme if it is already installed. Make sure to back up any existing themes before proceeding.

> **Note for snaps:** To use these icons with snaps, copy the application's `.desktop` file from `/var/lib/snapd/desktop/applications/name-of-the-snap-application.desktop` to `$HOME/.local/share/applications/`. Then, edit the file with a text editor and change the `Icon=` field to `Icon=name-of-the-icon.svg`.

---
<img width="1298" height="866" alt="image" src="https://github.com/user-attachments/assets/657034d8-f9cb-4dd7-afc3-7f161299e112" />
---
## Credits

This project is a blend of four incredible icon themes, which served as the foundation for WhiteSHW:

- **WhiteSur Icon Theme**: [https://github.com/vinceliuice/WhiteSur-icon-theme](#)
- **Win10Sur Icon Theme**: [https://github.com/yeyushengfan258/Win10Sur-icon-theme](#)
- **Sevi Icon Theme**: [https://github.com/TaylanTatli/Sevi](#)
- **Hatter Icon Theme**: [https://github.com/Mibea/Hatter](#)
