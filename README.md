# Fengshui Theme

Dark custom UI theme for Sublime Text 2 and Sublime Text 3. Heavily based on [Soda Theme](http://buymeasoda.com/) by Ian Hill.

*Deviations from jobedom/fengshui-theme*

I lightly modified the original fengshui theme by jobedom to fit my tastes a bit more:

- Made the tabs a bit taller so it didn't feel as cramped.
- Changed sidebar to not use images (use layer0.tint instead)
- Made sidebar slightly darker so it doesn't blend in with the main content area
- Overall made labels a bit brighter to increase contrast (and make it more readable for me)
- Added ability to use Seti UI Icons with the theme. See https://github.com/mrmartineau/SetiUI-Icons-Sublime for information on how to use that icon set

**feng shui**  
/ˌfɛŋ ˈʃuːi,ˌfʌŋ ˈʃweɪ/  
_noun_  
A system of laws considered to govern spatial arrangement and orientation in relation to the flow of energy (chi), and whose favourable or unfavourable effects are taken into account when designing.

Work on a canvas as free and clean as possible. Let the water and the air flow.

Project site: [https://github.com/green-arrow/fengshui-theme/](https://github.com/green-arrow/fengshui-theme)

## Design

![Fengshui Theme - Screenshot 1](https://raw.githubusercontent.com/green-arrow/fengshui-theme/master/screenshots/screenshot1.png)
![Fengshui Theme - Screenshot 2](https://raw.githubusercontent.com/green-arrow/fengshui-theme/master/screenshots/screenshot2.png)
![Fengshui Theme - Screenshot 3](https://raw.githubusercontent.com/green-arrow/fengshui-theme/master/screenshots/screenshot3.png)

### Scheme and font

The Fengshui screenshots use an included custom version of [Baara Dark scheme](https://packagecontrol.io/packages/Color%20Scheme%20-%20Baara%20Dark), also named *Fengshui* and adapted for Fengshui Theme. It's recommended to use it with the theme, including the following in your user settings.

    {
        "color_scheme": "Packages/Theme - Fengshui/Fengshui.tmTheme"
    }

The code font shown in the screenshots is [Fira Mono](https://mozilla.github.io/Fira/).

## Installation

Fengshui theme is designed to work with the latest development builds of Sublime Text, including [Sublime Text 2](http://www.sublimetext.com/dev) and [Sublime Text 3](http://www.sublimetext.com/3dev).

### Using Sublime Package Control

This customized version is not on Package Control. If you'd like to use Package Control, see [the original repo](https://github.com/jobedom/fengshui-theme) for directions on using the root theme.

### Using Git

Alternatively, if you are a git user, you can install the theme and keep up to date by cloning the repo directly into your `Packages` directory in the Sublime Text application settings area.

You can locate your Sublime Text `Packages` directory by using the menu item `Preferences -> Browse Packages...`.

While inside the `Packages` directory, clone the theme repository using the command below:

    git clone https://github.com/green-arrow/fengshui-theme/ "Theme - Fengshui"

### Download Manually

* Download the files using the GitHub .zip download option
* Unzip the files and rename the folder to `Theme - Fengshui`
* Find your `Packages` directory using the menu item  `Preferences -> Browse Packages...`
* Copy the folder into your Sublime Text `Packages` directory

## Activating the theme

To configure Sublime Text to use the theme, follow the instructions below for your specific version.

### Sublime Text 2

* Open your User Settings Preferences file `Sublime Text 2 -> Preferences -> Settings - User`
* Add (or update) your theme entry to be `"theme": "Fengshui.sublime-theme"`

**Example Sublime Text 2 User Settings**

    {
        "theme": "Fengshui.sublime-theme"
    }

### Sublime Text 3

* Open your User Settings Preferences file `Sublime Text -> Preferences -> Settings - User`
* Add (or update) your theme entry to be `"theme": "Fengshui.sublime-theme"`

**Example Sublime Text 3 User Settings**

    {
        "theme": "Fengshui.sublime-theme"
    }

## Additional Features

### Alternate Tab Styles

Fengshui Theme ships with two alternate UI tab styles.

By default, a square tab style is used. If you'd prefer to use the original curved tab style, add the following custom setting to your `Settings - User` file:

    "fengshui_classic_tabs": true

### Retina Resolution UI

Fengshui Theme has been designed to take advantage of retina resolution (high-dpi) displays.

## License

Fengshui Theme is licensed under the [Creative Commons Attribution-ShareAlike 3.0 License](http://creativecommons.org/licenses/by-sa/3.0/). You are free to share and remix the theme, however please abide by the license terms when doing so.

The following details apply to the Creative Commons license "author specified" components:

* Attribution example: Based on Fengshui Theme by Joaquín Bernal

* Naming guidelines: If you create and distribute a derivative theme, please give your theme a unique and original name that does not directly include "Fengshui Theme" (or a close variant) in the main project title, repo name or Package Control name.
