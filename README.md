# Atom Theme

### A dark interface and syntax theme for [Sublime Text](https://packagecontrol.io/packages/Atom%20Theme) based on [Atom.io](https://atom.io)

[![GitHub tag](https://img.shields.io/github/release/christopherfouquier/atom-theme.svg?style=flat-square)](https://github.com/christopherfouquier/atom-theme/releases)
[![Downloads](https://img.shields.io/packagecontrol/dt/Atom%20Theme.svg?colorB=80d4cd&style=flat-square)](https://packagecontrol.io/packages/Atom%20Theme)
[![Beerpay](https://beerpay.io/christopherfouquier/atom-theme/badge.svg?style=flat-square)](https://beerpay.io/christopherfouquier/atom-theme)

![](http://i.imgur.com/hHEOzMT.png)

[View a larger screenshot](http://i.imgur.com/hHEOzMT.png)

# Installation with [Package Control](https://packagecontrol.io/docs)

1. <kbd>Cmd</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> (OS X) <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> (Win/Linux)
2. Type `Package Control: Install Package`
3. Search `Atom Theme`

# Installation manually

* Download the [Package](https://github.com/christopherfouquier/atom-theme/archive/master.zip)
* Unzip the files and rename the folder to `Atom Theme`
* Find your `Packages` directory using the menu item  `Preferences -> Browse Packages...`
* Copy the folder into your Sublime Text `Packages` directory.

# Activating the Theme

Open your user settings file (click on `Preferences -> Settings - User`).

To activate the theme, add or replace your current theme settings with the code below.

```js
"theme": "atom.sublime-theme",
"color_scheme": "Packages/Atom Theme/atom.tmTheme"
```

#### !! IMPORTANT !!
Make sure to restart Sublime after installing and activating Atom Theme

# Recommended settings for a better experience

```js
"bold_folder_labels": true,
"caret_extra_width": 1,
"copy_with_empty_selection": false,
"drag_text": false,
"draw_white_space": "none",
"font_size": 13,
"highlight_line": true,
"line_padding_bottom": 1.5,
"line_padding_top": 1.5,
"open_files_in_new_window": false,
"preview_on_click": false,
"scroll_past_end": true,
"scroll_speed": 5.0,
"show_definitions": false,
"show_encoding": true,
"show_line_endings": true,
"tab_size": 2,
"translate_tabs_to_spaces": true,
"trim_trailing_white_space_on_save": true,
"word_wrap": false,
```

The font used in screenshot for the code is "Menlo"

# All Options and Defaults

```js
// Tabs Options
"atom_ui_tabs_large": false,
"atom_ui_tabs_medium": false,
"atom_ui_tabs_small": false
```
![](https://raw.githubusercontent.com/christopherfouquier/atom-theme/master/screenshots/tabs.png)