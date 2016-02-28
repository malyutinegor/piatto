# Piatto Theme

 Piatto is a very simple flat style theme for Sublime Text 3 Build 3062+.

Based on Soda Theme by Ian Hill - [http://buymeasoda.com/](http://buymeasoda.com/)

* File Type Icons based on Seti_UI - [https://github.com/ctf0/Seti_ST3](https://github.com/ctf0/Seti_ST3)
* Color Schemes based on Flat/Flat Dark by Ricardo Muniz Crespo [http://kotarodesign.com](http://kotarodesign.com)

## Design

![Piatto Light Theme](https://raw.github.com/samuelrafo/Piatto/master/images/piatto_light.png)

![Piatto Dark Theme](https://raw.github.com/samuelrafo/Piatto/master/images/piatto_dark.png)

## Installation

Piatto theme is designed to work with the latest development builds of Sublime Text 3 [Sublime Text 3](https://www.sublimetext.com/3), Build 3062+.

### Using Sublime Package Control

If you are using Will Bond's excellent [Sublime Package Control](http://wbond.net/sublime_packages/package_control), you can easily install Piatto Theme via the `Package Control: Install Package` menu item. The Piatto Theme package is listed as `Theme - Piatto` in the packages list.

### Download Manually

* Download the files using the GitHub .zip download option
* Unzip the files and rename the folder to `Theme - Piatto`
* Find your `Packages` directory using the menu item  `Preferences -> Browse Packages...`
* Copy the folder into your Sublime Text `Packages` directory

## Activating the theme

To configure Sublime Text to use the theme, follow the instructions.

* Open your User Settings Preferences file `Sublime Text -> Preferences -> Settings - User`
* Add (or update) your theme entry to be `"theme": "Piatto Light.sublime-theme",
"color_scheme": "Packages/Theme - Piatto/Piatto Light.tmTheme"`

**Example Sublime Text User Settings**

    {
        "theme": "Piatto Light.sublime-theme",
		"color_scheme": "Packages/Theme - Piatto/Piatto Light.tmTheme",
		"line_padding_top": 3,				// top line height
		"line_padding_bottom": 3,			// bottom line height
		"overlay_scroll_bars": "enabled",	// show scrollbars only when scrolling
		"bold_folder_labels": true,			// bold folder labels
		"highlight_modified_tabs":true,		// highlight modified tabs
		"highlight_line": true,				// highlight the current line
    }