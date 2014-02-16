# aapis/Flatland

## About

aapis/Flatland is a fork of the lovely Sublime theme Flatland, which is itself based on [Soda](https://github.com/buymeasoda/soda-theme). It contains all of the features in [flatland](https://github.com/thinkpixellab/flatland) as well as a few optional tweaks.

Currently only tested on ST2.

## Design

![Screen Shot!](https://raw.github.com/aapis/flatland/master/aapis_screenshots.png)

### Installation
If you are a git user, you can install the theme and keep up to date by cloning the repo directly into your `Packages` directory in the Sublime Text application settings area.

While inside the `Packages` directory, clone the theme repository using the command below:

```bash
git clone git://github.com/aapis/flatland.git "Theme - Flatland"
```


## Activating the Theme
Activate the theme by modifying your user preferences to include the following:

```javascript
{
  "theme": "Flatland Dark.sublime-theme",
  "color_scheme": "Packages/Theme - Flatland/Flatland Dark Krystal.tmTheme"
  //"color_scheme": "Packages/Theme - Flatland/Flatland Dark.tmTheme"
  //"color_scheme": "Packages/Theme - Flatland/Flatland Monokai.tmTheme"
}
```

If you need help locating your user preferences file, you can find it selecting "Preferences > Settings - User".

## Optional Settings
The following options can be set in your user preferences:

```javascript
{
  // square file tabs instead of rounded corners
  "flatland_square_tabs": true,

  // Monokai color scheme (SublimeText's default) with Flatland background color
  "color_scheme": "Packages/Theme - Flatland/Flatland Monokai.tmTheme",

  // a light theme for the sidebar
  "flatland_light_sidebar": true,

  // Ability to change row height of sidebar tree
  // Options: xsmall, small, medium, large, xlarge
  "flatland_sidebar_tree_xsmall" : true,

  //flat-styled tabs, active tab is light and inactive tabs are dark
  "flatland_flat_tabs_dark": true,

  //flat-styled tabs, active tab is dark and inactive tabs are light
  "flatland_flat_tabs_light": true,

  //icon-less folders
  "flatland_simple_filders": true,
}
