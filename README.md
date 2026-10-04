<div align="center">

# 🏯 Stronghold: Warlords | Persian Localization (پارسی‌ساز قلعه: جنگ‌سالاران)
### *Official ParsiSaz Community Translation & Dialogue Subtitle Mod for Stronghold: Warlords*

<br/>

[![ParsiSaz Portal](https://img.shields.io/badge/🌐_Documentation_Portal-parsisaz.github.io%2Fparsisaz-00f2fe?style=for-the-badge&logo=googlechrome)](https://parsisaz.github.io/parsisaz/)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg?style=for-the-badge)](https://www.gnu.org/licenses/gpl-3.0)
[![Locale](https://img.shields.io/badge/Locale-fa__IR-emerald?style=for-the-badge)](#-project-structure)
[![Maintainer](https://img.shields.io/badge/Maintained_by-Danial_Pahlavan-blue?style=for-the-badge&logo=github)](https://github.com/DanialPahlavan)

</div>

---

## 📖 Overview
This repository contains the Persian localization patch for **Stronghold: Warlords** (by Firefly Studios), organized following the **ParsiSaz 2026 Game Localization Architecture (L10N-STD-2026)**.

---

## 🗂️ Project Structure (L10N-STD-2026)

```
Stronghold-Warlords---Persian/
├── loc/                           # Decoupled Core Localization Data
│   ├── fa-IR/                     # Standard Persian XML strings
│   │   ├── fa.xml                 # Localized string keys & campaign dialogues
│   │   └── lang.txt               # Language configuration descriptor
│   └── glossaries/                # Medieval Asian warfare & castle terminology
├── game_assets/                   # Game Engine Drop-in Directory
│   └── assets/interface/i18n/     # Direct drop-in folder for Stronghold Warlords
├── HISTORY.md                     # Semantic Versioning Changelog
├── README.md                      # Project documentation
└── LICENSE                        # GNU General Public License v3
```

---

## 🚀 Installation Instructions

1. Download or clone this repository.
2. Copy `fa.xml` and `lang.txt` from `game_assets/assets/interface/i18n/` (or root) into your game folder:
   ```text
   <Stronghold_Warlords_Directory>\assets\interface\i18n\
   ```
3. Launch Stronghold: Warlords.
4. Persian subtitles and user interface will be enabled automatically!

---

## 🌐 Central Documentation & Bug Reports
For more details on engine hurdles, reverse engineering, and other games in the ecosystem:
👉 **[Open ParsiSaz Live Portal](https://parsisaz.github.io/parsisaz/)**
