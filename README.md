<h1 align="center">ProtonPlus (WIP)</h1>

<p align="center">
    <img src="https://img.shields.io/github/stars/Vysp3r/ProtonPlus?style=flat-square&label=%E2%AD%90%20Stars&branch=main&kill_cache=1%22">
    <a href="https://github.com/Vysp3r/ProtonPlus/releases/latest">
      <img alt="Latest Release (Semver)" src="https://img.shields.io/github/v/release/Vysp3r/ProtonPlus?style=flat-square&label=%F0%9F%9A%80%20Release">
    </a>
    <a>
      <img title="License" src="https://img.shields.io/github/license/Vysp3r/ProtonPlus?style=flat-square" />
    </a>
    <a href="https://t.me/ProtonPlusOfficial">
      <img title="Telegram" src="https://img.shields.io/endpoint?color=neon&style=flat-square&url=https%3A%2F%2Ftg.sumanjay.workers.dev%2FProtonPlusOfficial">
    </a>
</p>

<p align="center">
    <i>Join the telegram! — Don't forget to star the repo if you are enjoying the project!</i>
</p>

- - - -

ProtonPlus is a simple Proton version manager that make it easy to install and manage Proton versions. It works with Steam, Lutris, Heroic Games Launcher and Bottles. It was made in Vala with GTK4 and Libadwaita using GNOME Builder. <b>This project is still in its early phase, so please keep that in mind before using it.</b>

If you have any questions about ProtonPlus or want to share information with us, please go to one of the following places:

<img align="right" width=150 src="data/icons/hicolor/scalable/apps/com.vysp3r.ProtonPlus.svg" />

- [Github Discussions](https://github.com/Vysp3r/ProtonPlus/discussions)
- [Telegram Server](https://t.me/ProtonPlusOfficial)

*Before you file an [issue](https://github.com/Vysp3r/ProtonPlus/issues/new/choose), make sure you have read the [known issues](#-known-issues) section.*

**For more information, [read the documentation!](https://github.com/Vysp3r/ProtonPlus/wiki)**

- - - -

## 💾 Download

[<img align="center" width=150 src="https://camo.githubusercontent.com/1682ee5722ac262c660297d4541837e5c8765c7e239fa2a6ce7c3f4817a79283/68747470733a2f2f666c61746875622e6f72672f6173736574732f6261646765732f666c61746875622d62616467652d656e2e706e67" />](https://flathub.org/apps/details/com.vysp3r.ProtonPlus)

- - - -

## ✨ Features
- Install and manage Proton versions for Steam, Lutris, Bottles and Heroic Games Launcher
- And much more...

- - - -

## 👀 Preview
<img alt="ProtonPlus Preview" align="center" width="60%" src="Preview-1.png" />

- - - -

## 💥 Known Issues

- Heroic Games Launcher support not working
- Bottles support not working

- - - -

## 📝 TODOs

- Comment the code
- Document the project
- Add a game list with additional data like Deck compatibility and Anti-cheat status
- Add the ability to add custom locations
- Add games specific fixes (ex. Star Citizen)
- Add an update notification system

- - - -

## ⁉️ ProtonPlus vs ProtonUp-Qt

|                   | ProtonPlus                                  | ProtonUp-Qt                                      |
| :---------------- | :-----------------------------------------: | :----------------------------------------------: |
| **GUI Toolkit**   | [GTK4](https://gitlab.gnome.org/GNOME/gtk)  | [QT](https://www.qt.io/)                         |
| **Language**      | [Vala](https://gitlab.gnome.org/GNOME/vala) | [Python](https://www.python.org/)                |
| **Based on**      | Nothing                                     | [ProtonUp](https://github.com/AUNaseef/protonup) |
| **Looks best on** | [GNOME](https://gitlab.gnome.org/GNOME)     | [KDE](https://kde.org/)                          |

- - - -

### 🛠️ Building from Source

_Requirements_
- [git](https://github.com/git/git)
- [ninja](https://github.com/ninja-build/ninja)
- [meson](https://github.com/mesonbuild/meson)
- [gtk4](https://gitlab.gnome.org/GNOME/gtk/)
- [libadwaita-1](https://gitlab.gnome.org/GNOME/libadwaita)
- [json-glib-1.0](https://gitlab.gnome.org/GNOME/json-glib)
- [libsoup-3.0](https://gitlab.gnome.org/GNOME/libsoup)
- [libarchive](https://github.com/libarchive/libarchive)
- [desktop-file-utils](https://gitlab.freedesktop.org/xdg/desktop-file-utils)

**Installing**

- Install all dependencies (I'm using Fedora 37): `sudo dnf install git ninja-build meson gtk4-devel libadwaita-devel json-glib-devel libsoup3-devel libarchive-devel desktop-file-utils`
- Clone the GitHub repo: `git clone https://github.com/Vysp3r/ProtonPlus.git` & `cd ProtonPlus`
- Build the source: `meson build --prefix=/usr` & `cd build` & `ninja`
- (Optional) Install application: `ninja install`
- Start the application: `cd src` & `./protonplus`

- - - -

## 💖 Contributing
**Please read our [Contribution Guidelines](/CONTRIBUTING.md)**

All contributions are highly appreciated.

- - - -

## 📜 License

ProtonPlus is licensed under [GPL 3.0](/LICENSE.md)

```
 Copyright © 2022 Charles "Vysp3r" Malouin
 
 This program is free software: you can redistribute it and/or modify
 it under the terms of the GNU General Public License as published by
 the Free Software Foundation, either version 3 of the License, or
 (at your option) any later version.
 
 This program is distributed in the hope that it will be useful,
 but WITHOUT ANY WARRANTY; without even the implied warranty of
 MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
 GNU General Public License for more details.
 
 You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
```

**[⤴️ Back to Top](#ProtonPlus)**
