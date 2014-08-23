Icons
=====
Changing an app icon in OSX Mavericks is **_really_** simple, all you need is a `.icns` file and you will find a couples in the `icons` folder of the theme.

As an example of how to install an app icon, we will change `Mail.app`'s one. 

1. Go in the `icons` folder of this project, select the `Mail` file and `copy it (cmd + c)`.
2. Go to `/Applications`, `right click` the Mail app and select `Get Info`. _`Finder` is not located here. To find it go in `/System/Library/CoreServices`_
3. Select the Mail icon and `paste (cmd + v)` the new one. 

**That's it!**

Oh and of course, if the app was locked in the dock, you have to remove it from the dock and add it back, so the icon can be refreshed.

**SPECIAL ICONS (LIKE FINDER OR TRASH) INSTRUCTIONS.** These kind of icons need a special treatment. If you change the icon of the `Finder` app it will not update the Dock even after restarting. I don't really know why, but the `trash` and `Finder` icons are `.png` files and need to be installed specially for the Dock... _(You will find these files in the theme)_

1. Go to `/System/Library/CoreServices`, right click on `Dock` and select `Show Package Contents`.
2. And go into `Contents/Resources` to find these icons. Note that you will need a `@2x` image for Retina displays.

Additional instructions
-----------------------
You will find only a few icons in this project, that's why I added a `template.psd` in the elements folder so you can make your own iOS-like icons. **_Don't forget to submit them to me, if they are relevant I will add them to the project!_**

Here is how to get an icon ready for installation:

1. First, you will need a png file, at least a `256x256`, of your icon.
2. Go to http://iconverticons.com/online/ , upload your image.
3. Once the site finished to compile your file, click on the `Icns` button. This will download a `Finder Ready (.hqx)` archive.
4. Open the `.hqx` file.
5. There you go, you now have an app icon ready to be installed.