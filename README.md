# aapis/Flatland

## About

aapis/Flatland is a fork of the lovely Sublime theme Flatland, which is itself based on [Soda](https://github.com/buymeasoda/soda-theme). Currently only tested on 2.

## Design

![Screen Shot!](https://raw.github.com/thinkpixellab/flatland/master/screenshots.png)

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

  //give the tabs more of a flat appearance
  "flatland_flat_tabs": true,
}
