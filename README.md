# Piatto Theme

 Piatto is a very simple flat style theme for Sublime Text 2 and Sublime Text 3.

Based on Soda Theme by Ian Hill [http://buymeasoda.com/](http://buymeasoda.com/)

## Design

![Piatto Light Theme](https://raw.github.com/samuelrafo/Piatto/master/images/piatto_light.png)

![Piatto Dark Theme](https://raw.github.com/samuelrafo/Piatto/master/images/piatto_dark.png)

![Piatto Mandarine Theme](https://raw.github.com/samuelrafo/Piatto/master/images/piatto_mandarine.png)

## Installation

Piatto theme is designed to work with the latest development builds of Sublime Text, including [Sublime Text 2](http://www.sublimetext.com/dev) and [Sublime Text 3](http://www.sublimetext.com/3dev).

### Using Sublime Package Control

If you are using Will Bond's excellent [Sublime Package Control](http://wbond.net/sublime_packages/package_control), you can easily install Piatto Theme via the `Package Control: Install Package` menu item. The Piatto Theme package is listed as `Theme - Piatto` in the packages list.

### Download Manually

* Download the files using the GitHub .zip download option
* Unzip the files and rename the folder to `Theme - Piatto`
* Find your `Packages` directory using the menu item  `Preferences -> Browse Packages...`
* Copy the folder into your Sublime Text `Packages` directory

## Activating the theme

To configure Sublime Text to use the theme, follow the instructions below for your specific version.

### Sublime Text 2

* Open your User Settings Preferences file `Sublime Text 2 -> Preferences -> Settings - User`
* Add (or update) your theme entry to be `"theme": "Piatto Light.sublime-theme"`

**Example Sublime Text 2 User Settings**

    {
        "theme": "Piatto Light.sublime-theme"
    }

### Sublime Text 3

* Open your User Settings Preferences file `Sublime Text -> Preferences -> Settings - User`
* Add (or update) your theme entry to be `"theme": "Piatto Light 3.sublime-theme"`

**Example Sublime Text 3 User Settings**

    {
        "theme": "Piatto Dark 3.sublime-theme"
    }

### Sidebar Folder Icons

Piatto Theme has the ability to use folder icons in the sidebar.

If you'd like to use folder icons in the sidebar instead of the regular arrows, add the following custom setting to your `Settings - User` file:

    "piatto_folder_icons": true

![Piatto Folder Icons](https://raw.github.com/samuelrafo/Piatto/master/images/piatto_folder_icons.png)

### Overlay Scrollbars

If you'd like to use the overlay scrollbar, add the following custom setting to your Settings - User file:

```javascript
{
    "overlay_scroll_bars": "enabled"
}
```

## Optional


### Bold folder labels

```javascript
{
    "bold_folder_labels": true
}
```


### Color Scheme

```javascript
{
    "color_scheme": "Packages/Theme - Piatto/Piatto Light.tmTheme"
}
```
