# PoETrade Redesign v1.2.1
Unofficial redesign for the official Path of Exile trade website.

## Overview

This is just a few design changes to the PoE trade website to make it easier to use for now until GGG updates it in the future.

**This will probably stop working when design changes are made by GGG, but uninstalling is as easy as removing the CSS file later on**.

Official design (as of 2017/11/05).
![](https://i.imgur.com/UxkC6pC.png)

Vertical design (v1.2.1 as of 2017/11/05).
![](https://i.imgur.com/BrtCGkN.png)

Grid design (v1.2.1 as of 2017/11/05).
![](https://i.imgur.com/vcuYUEV.png)

## Installation

### Automatic

1. Install a stylesheet manager (used to put the CSS on the page).
    - [Stylus](https://addons.mozilla.org/en-US/firefox/addon/styl-us/) on Firefox or [Stylish](https://addons.mozilla.org/en-US/firefox/addon/stylish/) on Firefox.
    - [Stylish](https://chrome.google.com/webstore/detail/stylish-custom-themes-for/fjnbnpbmkenffdnngjfgmeleoegfcffe?hl=en) on Chrome.
2. Go to the style you wish to use:
    - Vertical style: https://userstyles.org/styles/150636/poe-trade-revamped-vertical
    - Grid style:  https://userstyles.org/styles/150637/poe-trade-revamped-grid
3. Click on the **Install Style** button on the website.
4. Browse to https://www.pathofexile.com/trade to use!

### Manual

1. Open your favourite stylesheet manager in your browser (I used Stylus on Firefox, Stylish on Chrome).
2. Create a new style and paste in either the `poetrade_grid.css` file or the `poetrade_vertical.css` file found on this repository.
3. Limit the domains to apply only to **URLs on the domain** `pathofexile.com` so that the CSS only affects the PoE trade website.

## Updating

To update, reinstall the CSS file or go to your stylesheet manager and click on 'Manage Styles'. There should be an option to 'Check for Updates' and this will prompt you to update to the newest version.

## Removal

1. Go to your stylesheet manager (Stylish or Stylus) and delete the stylesheet installed (should be called **PoE Trade Revamped - Vertical** or **PoE Trade Revamped - Grid**).
2. Uninstall your stylesheet manager if you no longer wish to use it.

## Changelog

1.2.1

- Minor style fixes to clean things up.
- Ensure boxes are always fixed at 45% width in Vertical style.
- Minor changes to padding/spacing.
- Add slight borders to differentiate sections better.

1.2

- Made the price field for Vertical style not as cropped (expands out, looks much better).

1.1

- Moved item prices to underneath the item picture.
- Cleaned up vertical style slightly.

1.0

- Added initial vertical and grid files.
