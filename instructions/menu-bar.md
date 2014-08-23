Menu Bar
======================

1. Install `Obsidian Menu Bar` application. Follow all the steps of the installer and confirm.
2. After restart of the session, it should have replaced every icons in the bar by their grey version. If not (this was my case), you will have to do it yourself (process explained below!). 

For those who want, you can use `Bartender` here.

Additional Instructions
-----------------------
You will find grey icons for many apps in the `Installer Content` folder in the Obsidian zip that you downloaded. But if you want to add your own icon to the menu bar, it is possible. All you will need is a `.tif | .tiff` file or a `.png` depending on the app.

For example, I will change the menu icon of the `Spectacle` app.

1. Go to `/Applications`, `right click` on `Spectacle` and select `Show Package Contents`. 
2. Go to `Contents/Resources`.
3. Here you will have to search the icon of the menu bar. The name of this file changes from an app to another so I'm not able to give you a pattern but you will probably find the words `menu` or `status` in it. In the example case, it is `Spectacle Status Item`.
4. Replace this image by the new one of the theme (located here `elements/icons/Spectacle Status Item.tif`).

**_NOTE:_** 

I added 3 menu bar icons to the project: Growl, Spectacle and Adobe Notifier. For the last one, you will find the menu icon to replace in `/Applications/Utilities/Adobe Application Manager/UWA`. `Right click` on `AAM Updates Notifier` and go to `Contents/Resources`.