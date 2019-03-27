# Brackets Color Scheme
[![License](https://img.shields.io/github/license/jwortmann/brackets-color-scheme.svg)](https://github.com/jwortmann/brackets-color-scheme/blob/master/LICENSE) [![Version](https://img.shields.io/github/release/jwortmann/brackets-color-scheme.svg)](https://github.com/jwortmann/brackets-color-scheme/tags) [![Downloads](https://img.shields.io/packagecontrol/dt/Brackets%20Color%20Scheme.svg)](https://packagecontrol.io/packages/Brackets%20Color%20Scheme)

This package for [Sublime Text 3](https://www.sublimetext.com/) provides two color schemes (light and dark) that are similar to the default themes of [Adobe Brackets](http://brackets.io/).

## Installation

The color scheme can be installed via Sublime Text's package manager [Package Control](https://sublime.wbond.net/installation).
From the Command Palette (<kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd>) choose `Package Control: Install Package` and search for `Brackets Color Scheme`.

Alternatively you can [download](https://github.com/jwortmann/brackets-color-scheme/archive/master.zip) and unzip the files from this repository and place them into your user directory.
To access the user directory, choose `Preferences > Browse Packages...` within Sublime Text and open the folder `User`.
Notice that there will be no automatic updates for the package without using Package Control.

The color scheme can be activated under `Preferences > Color Scheme...`.

## Screenshots

![Brackets Light](http://i.imgur.com/5HoE6I2.png)

![Brackets Dark](http://i.imgur.com/HZ0acdw.png)

## Color palette

|      | Brackets Light | Brackets Dark |
| ---- | -------------- | ------------- |
| Background | ![Background](http://via.placeholder.com/20/f8f8f8/f8f8f8) `#F8F8F8` | ![Background](http://via.placeholder.com/20/1d1f21/1d1f21) `#1D1F21` |
| Plain text | ![Plain text](http://via.placeholder.com/20/535353/535353) `#535353` | ![Plain text](http://via.placeholder.com/20/dddddd/dddddd) `#DDDDDD` |
| Comment | ![Comment](http://via.placeholder.com/20/949494/949494) `#949494` | ![Comment](http://via.placeholder.com/20/767676/767676) `#767676` |
| Blue | ![Blue](http://via.placeholder.com/20/446fbd/446fbd) `#446FBD` | ![Blue](http://via.placeholder.com/20/6c9ef8/6c9ef8) `#6C9EF8` |
| Orange | ![Orange](http://via.placeholder.com/20/e88501/e88501) `#E88501` | ![Orange](http://via.placeholder.com/20/d89333/d89333) `#D89333` |
| Green | ![Green](http://via.placeholder.com/20/6d8600/6d8600) `#6D8600` | ![Green](http://via.placeholder.com/20/85a300/85a300) `#85A300` |
| Violet | ![Violet](http://via.placeholder.com/20/8757ad/8757ad) `#8757AD` | ![Violet](http://via.placeholder.com/20/b77fdb/b77fdb) `#B77FDB` |
| Diff inserted | ![Diff inserted](http://via.placeholder.com/20/229922/229922) `#229922` | ![Diff inserted](http://via.placeholder.com/20/229922/229922) `#229922` |
| Diff deleted | ![Diff deleted](http://via.placeholder.com/20/dc322f/dc322f) `#DC322F` | ![Diff deleted](http://via.placeholder.com/20/dc322f/dc322f) `#DC322F` |

## Customization and backward compatibility

This color scheme uses color definitions and highlighting rules based on a JSON format, which was introduced in Sublime Text 3.1 (Build 3170).
The color scheme format allows to customize color variables and override or add user-specific highlighting rules, see [this example](https://www.sublimetext.com/docs/3/color_schemes.html#customization).

For older versions of Sublime Text (Sublime Text 2 & Sublime Text 3 Build < 3170) you can still download and unzip a [previous release](https://github.com/jwortmann/brackets-color-scheme/releases/tag/v1.0.4) of this package and place the corresponding `.tmTheme` files (TextMate format) into your user directory.

## License

Released under the [MIT License](https://github.com/jwortmann/brackets-color-scheme/blob/master/LICENSE).