<a id="readme-top"></a>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![GPL-3.0][license-shield]][license-url]

<div align="center">

# Halogen Amber

An orange/amber-themed Android home screen setup for **Total Launcher** powered by **KWGT** and **Icon Pack Studio**.

<img src="https://raw.githubusercontent.com/v3ndable/Halogen-Amber/refs/heads/main/Screenshot_Total-Launcher.png" width="300">

</div>

<details>
<summary>Table of Contents</summary>

- [About](#about)
- [Requirements](#requirements)
- [Downloads](#downloads)
- [Installation](#installation)
- [Additional Setup](#additional-setup)
- [License](#license)

</details>

## About
Halogen Amber is an orange/amber-themed Android home screen setup built for Total Launcher. It includes a custom launcher backup, a custom KWGT widget, and an Icon Pack Studio icon pack to recreate the complete look.

The project is based on the original [Halogen](https://github.com/Halodoesanope/Halogen.git) theme by [Halodoesanope](https://github.com/Halodoesanope), featuring a refreshed color palette and several visual tweaks while preserving the original design.

## Requirements

The following apps are required to use Halogen Amber:

| App | Notes |
|------|-------|
| [Total Launcher](https://play.google.com/store/apps/details?id=com.ss.launcher2) | Launcher |
| [Icon Pack Studio](https://play.google.com/store/apps/details?id=ginlemon.iconpackstudio) | Used to install the icon pack |
| [KWGT](https://play.google.com/store/apps/details?id=org.kustom.widget) | **Premium required** to import the widget |

> [!NOTE]
> Only **KWGT Premium** is required for this setup. Total Launcher and Icon Pack Studio can be used without their premium versions.

## Downloads

Download the following files before starting the installation:

| File | Description |
|------|-------------|
| [Halogen_Amber.zip](https://github.com/v3ndable/Halogen-Amber/raw/refs/heads/main/Halogen_Amber.zip) | Total Launcher backup containing the wallpaper and launcher layout. |
| [OnepanelAmber.kwgt](https://github.com/v3ndable/Halogen-Amber/raw/refs/heads/main/OnepanelAmber.kwgt) | KWGT widget preset. **Requires KWGT Premium.** |
| [Halogen Icons](https://share.iconpackstudio.com/feed/tdulmoUhpbNpb4Dg) | Icon Pack Studio project used to generate the icon pack. |

## Installation

### 1. Import the Total Launcher backup

1. Open **Total Launcher**.
2. Open the menu.
3. Go to **Backup Center**.
4. Tap **+** → **Import Backup**.
5. Select `Halogen_Amber.zip`.
6. Tap the **⋮** menu and choose **Restore**.

### 2. Import the KWGT widget

1. Open the **KWGT** app.
2. Tap **Select Folder**.
3. Create the **Kustom** folder if it doesn't already exist.
4. Using your file manager, copy `OnepanelAmber.kwgt` to `/Kustom/widgets`
5. Return to your home screen.
6. Tap the yellow widget placeholder.
7. Select **Create Widget**.
8. KWGT will open automatically.
9. Open the **Library** tab.
10. Select **OnepanelAmber**.
11. Grant any permissions requested by KWGT (for problems see Additional Setup).
12. Save the widget.

### 3. Set Total Launcher as your default launcher

Go to:

**Settings → Apps → Default apps → Home app**

Select **Total Launcher**.

### 4. Install the icon pack

1. Open **Icon Pack Studio**.
2. Search for **Halogen**.
3. Download the icon pack.
4. Open **Library**.
5. Select **Halogen** and tap **Apply**.
6. Once the APK has been generated, install it using your file manager.

Your home screen is now ready.

## Additional Setup

Since every phone has a different screen size and aspect ratio, you may need to make a few small adjustments.

### If KWGT shows "Restricted setting"

If notification access or another permission cannot be enabled because Android displays **Restricted setting**, go to:

**Settings → Apps → Kustom Widget → ⋮ → Allow restricted settings**

Then grant the required permissions again.

### General settings

Open **KWGT → Settings** and adjust:

* **Clock Mode**
* **Measurement Units**
* **Preferred Music Player**

### Weather

If the weather is incorrect:

1. Select your location.
2. Go to **Weather**.
3. Tap **Force Update**.

### Date format

The widget is designed for the `dd.MM` date format.

If your device uses another format, you will need to edit the corresponding text formulas inside the affected KWGT items.

### Accent color

The default accent color is:

**Amber (SAE/ECE)** — `#FFFF7E00`

To use a different accent color:

**KWGT → Globals → Color**

## License

This project is a modified fork of [Halogen](https://github.com/Halodoesanope/Halogen.git) by [Halodoesanope](https://github.com/Halodoesanope) and is licensed under the **GNU General Public License v3.0 (GPL-3.0)**, in accordance with the original project.

See the [LICENSE](LICENSE) file for the full license text.

[contributors-shield]: https://img.shields.io/github/contributors/v3ndable/Halogen-Amber.svg?style=for-the-badge
[contributors-url]: https://github.com/v3ndable/Halogen-Amber/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/v3ndable/Halogen-Amber.svg?style=for-the-badge
[forks-url]: https://github.com/v3ndable/Halogen-Amber/network/members
[stars-shield]: https://img.shields.io/github/stars/v3ndable/Halogen-Amber.svg?style=for-the-badge
[stars-url]: https://github.com/v3ndable/Halogen-Amber/stargazers
[issues-shield]: https://img.shields.io/github/issues/v3ndable/Halogen-Amber.svg?style=for-the-badge
[issues-url]: https://github.com/v3ndable/Halogen-Amber/issues
[license-shield]: https://img.shields.io/github/license/v3ndable/Halogen-Amber.svg?style=for-the-badge
[license-url]: https://github.com/v3ndable/Halogen-Amber/blob/master/LICENSE.txt
