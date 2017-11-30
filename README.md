# Superflat Adventures Theme

 Superflat Adventures is a very simple flat style theme for Sublime Text 3 Build 3062+.

Based on [Piatto Theme](https://github.com/samuelrafo/piatto) by Samuel Rafo and [Adventure Time](https://github.com/wilcoxky/Adventure_Time.tmTheme) color scheme by Kyle Wilcox.

## Design

![Superflat Adventures Theme](https://github.com/malyutinegor/superflat-adventures/raw/master/screenshot.png)

## Installation

Superflat Adventures theme is designed to work with the latest development builds of Sublime Text 3 [Sublime Text 3](https://www.sublimetext.com/3), Build 3062+.

### Using Package Control
* Press ctrl+shift+c.
* Enter "Package Control: Install Package".
* Enter "Theme - Superflat Adventures"

### Dependencies

Fonts:

* PT Sans
* Roboto

### Download Manually

* Download the files using the GitHub .zip download option
* Unzip the files and rename the folder to `Theme - Superflat Adventures`
* Find your `Packages` directory using the menu item  `Preferences -> Browse Packages...`
* Copy the folder into your Sublime Text `Packages` directory

## Activating the theme

To configure Sublime Text to use the theme, follow the instructions.

* Open your User Settings Preferences file `Sublime Text -> Preferences -> Settings - User`
* Add (or update) your theme entry to be `"theme": "Theme - Superflat Adventures.sublime-theme",
"color_scheme": "Packages/Theme - Superflat Adventures/Adventure Time.tmTheme"`

**Example Sublime Text User Settings**

    {
        "theme": "Superflat Adventures.sublime-theme",
		"color_scheme": "Packages/Theme - Superflat Adventures/Adventure Time.tmTheme",
		"line_padding_top": 3,				// top line height
		"line_padding_bottom": 3,			// bottom line height
		"overlay_scroll_bars": "enabled",	// show scrollbars only when scrolling
		"bold_folder_labels": true,			// bold folder labels
		"highlight_modified_tabs":true,		// highlight modified tabs
		"highlight_line": true,				// highlight the current line
    }
