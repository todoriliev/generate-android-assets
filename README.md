# Generate Android Assets

This [Sketch](http://bohemiancoding.com/sketch/) plugin automatically generates [all Android assets](http://developer.android.com/design/style/devices-displays.html)
(MDPI, HDPI, XHDPI, XXHDPI, and XXXHDPI) and drawable folders by using your XXHDPI layout design.

You can use Jonathan Chen's XXHDPI [Android GUI template](https://github.com/wikichen/sketch-android-kit) for starters.

## Installation

1. Navigate the Sketch menu bar to `Plugins ▸ Reveal Plugins Folder...`
2. Unzip and place the `generate-android-assets` folder into the revealed plugins directory. You can rename `generate-android-assets` to `Generate Android Assets`
3. You should find the `Generate Android Assets ▸ From XXHDPI` function under the Plugins menu in Sketch

## Usage

1. Select the Sketch layer(s) you want to export
2. Navigate the Sketch menu bar to `Plugins ▸ Generate Android Assets ▸ From XXHDPI`
3. Select the folder where you want to generate the five drawable folders and place the assets
4. You should see the following folders:

* drawable-mdpi
* drawable-hdpi
* drawable-xhdpi
* drawable-xxhdpi
* drawable-xxxhdpi

## Assumptions

The plugin assumes you design your layouts in XXHDPI, which means 3px = 1dp

## Other Android App Design Resources

If you are starting your first Android design, you might find the following links helpful:

* [Introduction to Android Design Principles](http://developer.android.com/design/get-started/principles.html)
* [Introduction to Material Design](https://www.google.com/design/spec/material-design/introduction.html)
* [Android Assets Studio](http://romannurik.github.io/AndroidAssetStudio/)
* [Design Patterns for Android](http://android.inspired-ui.com/)
* [Sketch App Resources for Android](http://www.sketchappsources.com/search_android.html)
* [Inspiration for Android App Design](http://www.android-app-patterns.com/)
* [Inspiration for Transitions Between App Screens](http://capptivate.co/)

## Credits

Many thanks to [Marius Mathiesen](https://github.com/zmalltalker), the original creator.

[Jonathan E. Chen](https://github.com/wikichen), the creator of the Android GUI template for Sketch.