# Blocks Theme

Blocks theme for and Sublime Text 3.


## Design

### Blocks Dark
![Blocks Dark](http://s22.postimg.org/oyfpmro5t/Blocks_Dark_preview.png)

### Blocks Light
![Blocks Light](http://s23.postimg.org/uajxg92t7/Blocks_Light_preview.png)

## Installation

Blocks theme is designed to work with [Sublime Text 3](http://www.sublimetext.com/3dev).

### Using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo directly into your `Packages` directory in the Sublime Text application settings area.

You can locate your Sublime Text `Packages` directory by using the menu item `Preferences -> Browse Packages...`.

While inside the `Packages` directory, clone the theme repository using the command below:

    git clone https://github.com/ilikecookies/theme-blocks/ "Theme - Blocks"

### Download Manually

* Download the files using the GitHub .zip download option
* Unzip the files and rename the folder to `Theme - Blocks`
* Find your `Packages` directory using the menu item  `Preferences -> Browse Packages...`
* Copy the folder into your Sublime Text `Packages` directory

## Activating the theme

To configure Sublime Text to use the theme, follow the instructions below.

### Blocks Light

* Open your User Settings Preferences file `Sublime Text -> Preferences -> Settings - User`
* Add (or update) your theme entry to be `"theme": "Blocks Light.sublime-theme"`
* RESTART Sublime Text 3

    {
        "theme": "Blocks Light.sublime-theme"
    }

### Blocks Dark

* Open your User Settings Preferences file `Sublime Text -> Preferences -> Settings - User`
* Add (or update) your theme entry to be `"theme": "Blocks Dark.sublime-theme"`
* RESTART Sublime Text 3

    {
        "theme": "Blocks Dark.sublime-theme"
    }

## Additional Features

### Sidebar Folder Icons

Blocks Theme has the ability to use folder icons in the sidebar.

If you'd like to use folder icons in the sidebar instead of the regular arrows, add the following custom setting to your `Settings - User` file:

    "blocks_folder_icons": true

### Retina Resolution UI

Blocks Theme has been designed to take advantage of retina resolution (high-dpi) displays.


### Theme Customisation

Sublime Text provides an elegant way to tweak existing themes without having to duplicate or maintain a separate copy of the original theme. If there are aspects of Blocks Theme that you would like to adjust, take a look at the [theme customisation](https://github.com/buymeasoda/soda-theme/wiki/Theme-customisation) wiki page.

## Bonus!!!

The Blocks Light theme goes well with Stephen Kamenar's Color Scheme [WebDeveloperBright](https://github.com/farzher/Sublime-Text-Themes)

The Blocks Dark theme goes well with Jon Schlinkert's Color Scheme [MonokaiExtended](https://github.com/jonschlinkert/sublime-monokai-extended)


### Syntax Highlighting Color Schemes

The Blocks theme uses a custom syntax highlighting color scheme.

If you'd like to use the syntax highlighting schemes: 

* Locate the `tmtheme` file in `Packages/Theme - Blocks/Color Schemes/`
* Copy and paste the `tmtheme` file in the Sublime Text `Packages/User` folder
* Enable the colour scheme via `Preferences -> Color Scheme -> User`

### Use thinner tabs
In your User Settings file, add the following line `"blocks_thin_tabs": true,`

### Use sidebar folder icons 

In your User Settings file, add the following line `"blocks_folder_icons": true,`

## Development

Please note, Sublime Text dev builds move quickly and changes can occur with the theme API between releases, so there may be occasions where the theme doesn't quite work with a brand new dev release.

## License

Based on Flat UI Theme by acondiff (https://github.com/acondiff)

