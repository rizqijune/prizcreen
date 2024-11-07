<div align="center">
	<img width="80" height="80" src="https://cdn.jsdelivr.net/gh/Tomotoes/images/blog/icon.png" alt="tomoto">
	<br>
	<h1>Prizcreen</h1>
	<sub>Built with ❤︎ by <a href="https://tomotoes.com">Simon Ma</a> - Forked with ❤︎ by <a href="https://ud.me/rizqijune.nft">rizqijune</a></sub>
</div>
<hr/>
<p align="center">✨ <strong>A GUI application for scrcpy</strong></p>
<h3 align="center"> <strong> NOTE: Simon have no energy to continue maintenance, so I forked it.</h3>

<p align="center">
  <a href="https://github.com/feross/standard">
    <img src="https://img.shields.io/badge/code%20style-standard-green.svg?style=flat-square" alt="">
  </a>
  <a href="https://github.com/rizqijune/przcreen/releases">
    <img alt="GitHub Downloads (all assets, latest release)" src="https://img.shields.io/github/downloads/rizqijune/przcreen/latest/total">
  </a>
   <a href="https://travis-ci.org/rizqijune/przcreen/builds">
    <img src="https://img.shields.io/travis/Tomotoes/scrcpy-gui.svg?style=flat-square" alt="">
  </a>
  <a href="https://github.com/rizqijune/przcreen/releases/latest">
    <img alt="GitHub Release" src="https://img.shields.io/github/v/release/rizqijune/przcreen">
  </a>
  <a href="https://opensource.org/licenses/GPL-3.0/"><img src="https://badges.frapsoft.com/os/gpl/gpl.svg?style=flat-square"></a>
  <a href="https://github.com/rizqijune/przcreen/issues"><img src="https://img.shields.io/badge/contributions-unavailable-red.svg?style=flat-square"></a>
</p>

# 💡Introduction
<div align=center><img width="508" height="785.6" src="https://cdn.jsdelivr.net/gh/Tomotoes/images/scrcpy-gui/English.gif"/></div>
<div align=center><img src="./screenshot.gif"/></div>

**Prizcreen** is a graphical interface for [scrcpy](https://github.com/Genymobile/scrcpy), allowing you to control and mirror Android devices to your desktop with ease. With a sleek and intuitive interface, Prizcreen simplifies the process of mirroring and interacting with your Android device, offering the full power of scrcpy without the need for complex terminal commands.

## ✨Features

- **lightness** (native, displays only the device screen)
- **performance** (30~60fps)
- **quality** (1920×1080 or above)
- **low latency** ([35~70ms](https://github.com/Genymobile/scrcpy/pull/646))
- **low startup time** (~1 second to display the first image)
- **non-intrusiveness** (nothing is left installed on the device)
- **No need for ROOT**
- **Wired and wireless can be connected**
- **You can adjust the interface and bit rate**
- **Pictures can be cut at will, with a screen recording**
- **Support multiple devices to screen at the same time**
- **Control your phone with your computer's keyboard and mouse**
- **Mobile computer sharing clipboard**
- **Automatically detect USB connected apps**
- **Can directly add the LAN IP of the device to achieve the effect of wireless control**
- **Automatically save the connected IP address, automatically reminder the next time you enter**
- **Support device alias**
- **Support for Chinese and English**
- **Tray menu**

## Shortcuts

| Action                                  | Shortcut                      | Shortcut (macOS)             |
| --------------------------------------- | ----------------------------- | ---------------------------- |
| Switch fullscreen mode                  | `Ctrl`+`f`                    | `Cmd`+`f`                    |
| Resize window to 1:1 (pixel-perfect)    | `Ctrl`+`g`                    | `Cmd`+`g`                    |
| Resize window to remove black borders   | `Ctrl`+`x` \| *Double-click¹* | `Cmd`+`x` \| *Double-click¹* |
| Click on `HOME`                         | `Ctrl`+`h` \| *Middle-click*  | `Ctrl`+`h` \| *Middle-click* |
| Click on `BACK`                         | `Ctrl`+`b` \| *Right-click²*  | `Cmd`+`b` \| *Right-click²*  |
| Click on `APP_SWITCH`                   | `Ctrl`+`s`                    | `Cmd`+`s`                    |
| Click on `MENU`                         | `Ctrl`+`m`                    | `Ctrl`+`m`                   |
| Click on `VOLUME_UP`                    | `Ctrl`+`↑` *(up)*             | `Cmd`+`↑` *(up)*             |
| Click on `VOLUME_DOWN`                  | `Ctrl`+`↓` *(down)*           | `Cmd`+`↓` *(down)*           |
| Click on `POWER`                        | `Ctrl`+`p`                    | `Cmd`+`p`                    |
| Power on                                | *Right-click²*                | *Right-click²*               |
| Turn device screen off (keep mirroring) | `Ctrl`+`o`                    | `Cmd`+`o`                    |
| Expand notification panel               | `Ctrl`+`n`                    | `Cmd`+`n`                    |
| Collapse notification panel             | `Ctrl`+`Shift`+`n`            | `Cmd`+`Shift`+`n`            |
| Copy device clipboard to computer       | `Ctrl`+`c`                    | `Cmd`+`c`                    |
| Paste computer clipboard to device      | `Ctrl`+`v`                    | `Cmd`+`v`                    |
| Copy computer clipboard to device       | `Ctrl`+`Shift`+`v`            | `Cmd`+`Shift`+`v`            |
| Enable/disable FPS counter (on stdout)  | `Ctrl`+`i`                    | `Cmd`+`i`                    |

*¹Double-click on black borders to remove them.*
*²Right-click turns the screen on if it was off, presses BACK otherwise.*

## Prerequisites

To run Prizcreen, you'll need:

- **Android device** with Developer Mode and USB debugging enabled.
- **scrcpy**: Prizcreen is a GUI wrapper for [scrcpy](https://github.com/Genymobile/scrcpy). You’ll need to have scrcpy installed. Please follow the installation instructions on the [scrcpy GitHub page](https://github.com/Genymobile/scrcpy) if you haven't already installed it.

## Installation

This project was generated with [electron-vue](https://github.com/SimulatedGREG/electron-vue)@[8fae476](https://github.com/SimulatedGREG/electron-vue/tree/8fae4763e9d225d3691b627e83b9e09b56f6c935) using [vue-cli](https://github.com/vuejs/vue-cli). Documentation about the original structure can be found [here](https://simulatedgreg.gitbooks.io/electron-vue/content/index.html).

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:9080
npm run dev

# build electron application for production
npm run build

# lint all JS/Vue component files in `src/`
npm run lint
```

## Usage

1. Open the **Prizcreen** app.
2. Select your connected Android device from the dropdown.
3. Hit the "Start" button to begin mirroring and controlling your Android device from your desktop.
4. Customize the settings based on your preferences, such as screen resolution, bit rate, etc.

## Contributing
### Unavailable at the moment
~~Feel free to fork this project and submit pull requests. If you find any issues or want to request a feature, please open an issue in the [GitHub Issues section](https://github.com/rizqijune/prizcreen/issues).~~

## License

Distributed under the GNU GPLv3 License. See [LICENSE](LICENSE) for more information.
