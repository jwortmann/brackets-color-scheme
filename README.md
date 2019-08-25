# Brackets Color Scheme

[![License](https://img.shields.io/github/license/jwortmann/brackets-color-scheme)](https://github.com/jwortmann/brackets-color-scheme/blob/master/LICENSE)
[![Version](https://img.shields.io/github/v/tag/jwortmann/brackets-color-scheme?label=version)](https://github.com/jwortmann/brackets-color-scheme/tags)
[![Downloads](https://img.shields.io/packagecontrol/dt/Brackets%20Color%20Scheme)](https://packagecontrol.io/packages/Brackets%20Color%20Scheme)

This package for [Sublime Text 3](https://www.sublimetext.com/) provides two color schemes (light and dark) that are similar to the built-in themes of [Adobe Brackets](http://brackets.io/).

## Installation

The color scheme can be installed via Sublime Text's package manager [Package Control](https://packagecontrol.io/installation).
From the command palette (<kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd>) choose `Package Control: Install Package` and search for `Brackets Color Scheme`.

Alternatively you can [download](https://github.com/jwortmann/brackets-color-scheme/archive/master.zip) and unzip the files from this repository and place them into a folder in the packages directory of Sublime Text, e.g. the `Packages/User` package.
To access the packages directory, choose `Preferences > Browse Packages...` from the Sublime Text menu.
Notice that there will be no automatic updates for this package if not using Package Control.

The color scheme can then be activated from the menu under `Preferences > Color Scheme...` or via the `UI: Select Color Scheme` command from the command palette.

## Preview

![Brackets Light](https://i.imgur.com/hCvUKuH.png)

![Brackets Dark](https://i.imgur.com/KLOsBrO.png)

The font used in the preview images is [Fira Mono](https://github.com/mozilla/Fira).

## Color palette

| Color variable | Brackets Light | Brackets Dark | Example usage |
| -------------- | -------------- | ------------- | ------------- |
| | ![background](http://via.placeholder.com/20/f8f8f8/f8f8f8) `#F8F8F8` | ![background](http://via.placeholder.com/20/1d1f21/1d1f21) `#1D1F21` | background |
| textcolor | ![textcolor](http://via.placeholder.com/20/535353/535353) `#535353` | ![textcolor](http://via.placeholder.com/20/dddddd/dddddd) `#DDDDDD` | plain text, variables, operators, punctuations |
| grey | ![grey](http://via.placeholder.com/20/949494/949494) `#949494` | ![grey](http://via.placeholder.com/20/767676/767676) `#767676` | comments |
| blue | ![blue](http://via.placeholder.com/20/446fbd/446fbd) `#446FBD` | ![blue](http://via.placeholder.com/20/6c9ef8/6c9ef8) `#6C9EF8` | keywords, intrinsic/library functions, tags |
| orange | ![orange](http://via.placeholder.com/20/e88501/e88501) `#E88501` | ![orange](http://via.placeholder.com/20/d89333/d89333) `#D89333` | strings, constants, function arguments |
| green | ![green](http://via.placeholder.com/20/6d8600/6d8600) `#6D8600` | ![green](http://via.placeholder.com/20/85a300/85a300) `#85A300` | numbers, HTML/XML tag attributes |
| violet | ![violet](http://via.placeholder.com/20/8757ad/8757ad) `#8757AD` | ![violet](http://via.placeholder.com/20/b77fdb/b77fdb) `#B77FDB` | user defined functions, JSON keys, CSS property names |
| pink | ![pink](http://via.placeholder.com/20/d33682/d33682) `#D33682` | ![pink](http://via.placeholder.com/20/d85896/d85896) `#D85896` | annotations, headings in markup languages |
| red | ![red](http://via.placeholder.com/20/dc322f/dc322f) `#DC322F` | ![red](http://via.placeholder.com/20/dc322f/dc322f) `#DC322F` | invalid syntax |
| green2 | ![green2](http://via.placeholder.com/20/229922/229922) `#229922` | ![green2](http://via.placeholder.com/20/229922/229922) `#229922` | diff inserted |
| red2 | ![red2](http://via.placeholder.com/20/dd4444/dd4444) `#DD4444` | ![red2](http://via.placeholder.com/20/dd4444/dd4444) `#DD4444` | diff deleted |

## Customization and backward compatibility

This color scheme uses color definitions and highlighting rules based on a JSON format, which was introduced in Sublime Text 3.1 (Build 3170).
The color scheme format allows to customize color variables and override or add user-specific highlighting rules, see [this example](https://www.sublimetext.com/docs/3/color_schemes.html#customization) in the official documentation.
For the color variable names used by this scheme, refer to the color palette above.

For older versions of Sublime Text (Sublime Text 2 & Sublime Text 3 Build < 3170) you can still download and unzip a [previous release](https://github.com/jwortmann/brackets-color-scheme/releases/tag/v1.0.4) of this package and place the corresponding `.tmTheme` files (TextMate format) into e.g. the `Packages/User` package.
