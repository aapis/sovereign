# aapis/Flatland

## About

Flatland is a simple theme and accompanying color scheme for Sublime Text 2 & 3. It is mostly derived from  [Soda](https://github.com/buymeasoda/soda-theme), the right place to start for any custom theme development for Sublime. Thanks Soda!

## Design

![Screen Shot!](https://raw.github.com/thinkpixellab/flatland/master/screenshots.png)

### Installation
Alternatively, if you are a git user, you can install the theme and keep up to date by cloning the repo directly into your `Packages` directory in the Sublime Text application settings area.

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
  "flatland_light_sidebar": true
}
```
