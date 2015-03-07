# Sublime Text 3

Packages and associated settings I use in Sublime Text 3.

## Packages

#### Package Control - [Link](https://sublime.wbond.net/installation)

From here on out, the rest of the packages are installed using Package Control in Sublime Text 3. You can search for these packages by:

1. Bring up the Command Palette with the menu item `Tools > Command Palette` or with `⌘+shift+p` on a Mac
2. Type "install" and select "Package Control: Install Package"

* AngularJS
* Babel
* Better CoffeeScript
* BracketHighlighter
* GitGutter
* Handlebars
* HTML-CSS-JS Prettify
* Inc-Dec-Value
* LESS
* SCSS

## Settings

#### Settings - User
```json
{
	"bold_folder_labels": true,
	"color_scheme": "Packages/Theme - Spacegray/base16-ocean.dark.tmTheme",
	"draw_white_space": "all",
	"ensure_newline_at_eof_on_save": true,
	"folder_exclude_patterns":
	[
		".sass-cache",
		".svn",
		".git",
		".hg",
		"bower_components",
		"node_modules",
		"tmp"
	],
	"font_face": "Monaco",
	"font_size": 10,
	"highlight_line": true,
	"ignored_packages":
	[
		"CSS",
		"Vintage"
	],
	"open_files_in_new_window": false,
	"rulers":
	[
		80
	],
	"tab_size": 2,
	"theme": "Spacegray.sublime-theme",
	"translate_tabs_to_spaces": true,
	"trim_trailing_white_space_on_save": true
}
```
