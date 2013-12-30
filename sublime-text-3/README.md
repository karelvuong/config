# Sublime Text 3

Packages and associated settings I use in Sublime Text 3.

## Theme

## Color Scheme

## Packages

#### Package Control - [Link](https://sublime.wbond.net/installation)

From here on out, the rest of the packages are installed using Package Control in Sublime Text 3. You can search for these packages using the menu item `Tools > Command Palette` or with `cmd+shift+p` on a Mac.

#### Browser Refresh

#### LESS

#### Preference Editor

#### SublimeLinter

##### SublimeLinter-annotations
##### SublimeLinter-coffeelint
##### SublimeLinter-csslint
##### SublimeLinter-html-tidy
##### SublimeLinter-jsl
##### SublimeLinter-json

#### Trimmer

## Settings

#### Settings - User
```json
{
    "bold_folder_labels": true,
    "color_scheme": "Packages/User/base16-ocean.dark (SL).tmTheme",
    "draw_white_space": "all",
    "ignored_packages":
    [
        "Vintage"
    ],
    "open_files_in_new_window": false,
    "tab_size": 4,
    "theme": "Spacegray.sublime-theme",
    "translate_tabs_to_spaces": true,
    "trim_trailing_white_space_on_save": true
}
```

#### Key Bindings - User
```json
[
    { "keys": ["command+r"], "command": "browser_refresh", "args": {
        "auto_save": true,
        "delay": 0.5,
        "activate_browser": true,
        "browser_name" : "all"
    }},
    { "keys": ["super+shift+r"], "command": "show_overlay", "args": {
        "overlay": "goto",
        "text": "@"
    }}
]
```