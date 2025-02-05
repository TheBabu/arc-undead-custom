# Arc-Undead-Custom
#### A simplified GTK Arc Theme

This a modified version of UndeadLeech's theme: https://github.com/chrisduerr/arc-undead

Disclaimer: Credit for most of this goes to the original Arc Theme.
You can find it here: https://github.com/horst3180/arc-theme

### Installation

All you need to do to install this theme in its base configuration is running `install.sh` as root (or any other user that has access to `/usr/share/themes`) and the theme is ready to use.

### Hacking
This theme aims to be easy to configure and change. If you want to edit the gtk3 theme, you only have to edit the `gtk.css`.
For the gtk2 theme you'll have to edit the `gtkrc` file. Both gtk2 and gtk3 have an `assets.svg` file for the images.

There are only a few colors which have been used in the creation of this theme, these are:
 * `#282828` as primary background color
 * `#222222` as secondary background color
 * `#d0d0d0` as primary foreground color
 * `#4278b7` as highlight color

I have changed a bunch of various other colors, and added back the rounded edges that were previously removed from UndeadLeech's theme.

Once you change the `assets.svg` file you'll have to regenerate the assets using the `render-assets.sh` script.
This requires `inkscape` and optionally `optipng` for compressing the output images.

If you want to change the name of the theme, all you have to do is edit the `index.theme` file and replace every occurance of `Arc-Undead-Custom` with the new name.

After changing anything, you'll have to reinstall the theme using the `install.sh` script.

## Screenshots

### GTK3
![Screenshot_2024-01-01_09-48-25](https://github.com/TheBabu/arc-undead-custom/assets/24832107/20e956b6-23c9-4c86-8972-e034a96099fa)
![Screenshot_2024-01-01_09-48-33](https://github.com/TheBabu/arc-undead-custom/assets/24832107/79bafd62-c890-4cbf-a34b-7e25bcb0c1ec)
![Screenshot_2024-01-01_09-48-43](https://github.com/TheBabu/arc-undead-custom/assets/24832107/779aca56-cdc1-4d23-9274-1a4698a36370)
