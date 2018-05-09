Android Asset Studio
====================

## Disclaimer
This fork has been modified in a way that no background will be added to the generated app launcher icons. The purpose of that is being able to generate a launcher icon with just a drop shadow, which you can then import in Android Studio by right clicking Res -> New -> Image Asset. You can then set the newly generated icon as the foreground and select your own background. That will generate proper adaptive icons, which you can then use in your app.

**[Open the Android Asset Studio](https://tibbi.github.io/AndroidAssetStudio/)**

**[See the older version](https://tibbi.github.io/AndroidAssetStudio/older-version/) if you're having trouble with the new version**

A web-based set of tools for generating graphics and other assets that would eventually be in an Android application's res/ directory.

Currently available asset generators are for:

- Launcher icons
- Action bar icons
- Notification icons
- Generic square icons
- Simple nine-patches

## Building the tool

To build, ensure you have `node` and `npm` installed, and run:

    $ npm install

Once dependencies are installed, run with `gulp`:

    $ gulp serve

## Related (third-party) projects

- [Android Asset Studio Desktop Apps](https://androidassetstudio.codeplex.com/)
