# Neon Suede Theme

Yet another `subtle`,`elegant` & `unobstructive` theme aimed at the philosophy of `simplicity`, `aesthetic` and `readability`, for the awesome [Typora](https://typora.io/) markdown editor and reader.

Tweaked for both English🇺🇸 & 中文🇨🇳. Works on both macOS & Windows.

Ships with **Light** 🌞 & **Dark** 🌑 color schemes. [Download](https://github.com/ryolambert/typora-neon-suede-theme/releases/latest)

## Quick Glance

Light mode:

<p align="center">
  <img src="https://github.com/ryolambert/typora-neon-suede-theme/raw/master/assets/neon-suede-light-demo.png" alt="neon-suede-light-demo" width="887"/>
</p>

Dark mode:

<p align="center">
  <img src="https://github.com/ryolambert/typora-neon-suede-theme/raw/master/assets/neon-suede-dark-demo.png" alt="neon-suede-dark-demo" width="887"/>
</p>

## Full Preview

<details><summary>Show light preview:</summary>
<p align="center">
  <img src="https://github.com/ryolambert/typora-neon-suede-theme/raw/master/assets/light-preview.png" alt="light-preview" width="648"/>
</p>
</details>

<details><summary>Show dark preview:</summary>
<p align="center">
  <img src="https://github.com/ryolambert/typora-neon-suede-theme/raw/master/assets/dark-preview.png" alt="dark-preview" width="648"/>
</p>
</details>

## Installation

[Download theme stylesheets](https://github.com/ryolambert/typora-neon-suede-theme/releases/latest) of the platform you work on and color schemes you like. Copy it into the themes folder of Typora. Select theme name (eg. `Neon Suede Light Macos`) form the theme list to apply it. You may restart Typora once to help it discover the theme file.

For detailed reference, please see [Install Theme](https://theme.typora.io/doc/Install-Theme/).

## How to Build

Neon Suede is now written in SASS and the `dist\` folder has been dropped from this repo. You may directly download distributed builds from [release portal](https://github.com/ryolambert/typora-neon-suede-theme/releases/latest).

If you need to manually build the theme, with `npm` installed, you could easily compile source SCSS to CSS Typora could read by running:

```
npm i --only=dev
npx gulp build
```

Compiled & optimized CSS files can then be found in `dist\`:

```
[16:06:41] Using gulpfile ~/typora-neon-suede-theme/gulpfile.js
[16:06:41] Starting 'build'...
[16:06:41] Finished 'build' after 227 ms
```



## Compatibility

Neon Suede is both test on `macOS 10.13.6` and `Windows 10 version 1703`. However, it has not been tested on `Linux` thoroughly yet and will be tested in future.

Font fallback list is tweaked for both English and Chinese, on both macOS and Windows. Font weight values have been slightly adjusted on Windows to match Windows-specific rendering characteristic.

## Known Issues

- ~~Borders of buttons on all platforms and context menu on *Windows* are too bright in *Dark* mode.~~
- Text color & Background of Preference Panel on *Windows* is too bright in *Dark* mode.
- Colors and layouts of math block on all platforms need to be inspected and tuned.
- Font fallback list and rendering effect has not been tested on *Linux*.
- Text thickness & font family rendered may not be consistent on Windows of different builds or in different languages.
- Colors of tooltips need to adjusted in dark mode.

> Made with 💖 by Ryo Lambert 2019
