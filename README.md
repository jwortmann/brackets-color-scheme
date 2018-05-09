# Brackets Color Scheme
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/jwortmann/brackets-color-scheme/blob/master/LICENSE)

This package for Sublime Text provides two color schemes (light and dark) similar to the [Adobe Brackets](http://brackets.io/) text editor.

## Installation

An installation via [Package Control](https://sublime.wbond.net/installation) is recommended. The color scheme is listed as `Brackets Color Scheme` in the packages list.

Alternatively you can perform a manual installation:

1. Open the packages directory of Sublime Text, e.g. by using `Preferences > Browse Packages...` within Sublime Text.
2. [Download](https://github.com/jwortmann/brackets-color-scheme/archive/master.zip) and unzip the files from this repository or clone it using the command

        git clone https://github.com/jwortmann/brackets-color-scheme.git "Brackets Color Scheme"

## Screenshots

![Brackets Light](http://i.imgur.com/5HoE6I2.png)

![Brackets Dark](http://i.imgur.com/HZ0acdw.png)

## Color palette

|      | Brackets Light | Brackets Dark |
| ---- | -------------- | ------------- |
| Background | ![Background](http://via.placeholder.com/20/f8f8f8/f8f8f8) `#F8F8F8` | ![Background](http://via.placeholder.com/20/1d1f21/1d1f21) `#1D1F21` |
| Text | ![Text](http://via.placeholder.com/20/535353/535353) `#535353` | ![Text](http://via.placeholder.com/20/dddddd/dddddd) `#DDDDDD` |
| Comment | ![Comment](http://via.placeholder.com/20/949494/949494) `#949494` | ![Comment](http://via.placeholder.com/20/767676/767676) `#767676` |
| Blue | ![Blue](http://via.placeholder.com/20/446fbd/446fbd) `#446FBD` | ![Blue](http://via.placeholder.com/20/6c9ef8/6c9ef8) `#6C9EF8` |
| Orange | ![Orange](http://via.placeholder.com/20/e88501/e88501) `#E88501` | ![Orange](http://via.placeholder.com/20/d89333/d89333) `#D89333` |
| Green | ![Green](http://via.placeholder.com/20/6d8600/6D8600) `#6d8600` | ![Green](http://via.placeholder.com/20/85a300/85a300) `#85A300` |
| Violet | ![Violet](http://via.placeholder.com/20/8757ad/8757ad) `#8757AD` | ![Violet](http://via.placeholder.com/20/b77fdb/b77fdb) `#B77FDB` |

## New color scheme format in Sublime Text 3.1 (>= Build 3170)

Sublime Text 3.1 (Build 3170) introduced a new color scheme format based on JSON, which seems to have some advantages
to the previous TextMate `.tmTheme` format. This release of the Brackets Color Scheme for Sublime Text includes color
definitions and (slightly improved) highlighting rules in the new file format, as well as the old `.tmTheme` files with
the same base filenames. Current releases of Sublime Text should automaticly use the new `.sublime-color-scheme` files
and ignore the files with same filenames in the old file format. However, if any kind of issues occur with the new
files, you can still download the old `.tmTheme` files from this GitHub repository and place them into your user
directory of Sublime Text.

With the new color scheme format you can also customize color variables and override/add user-specific highlighting
rules, see [this example](https://www.sublimetext.com/docs/3/color_schemes.html#customization).

## License

The MIT License (MIT)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.