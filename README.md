# What is this?
Cook, Serve, Delicious! 2!! is the massive sequel to the surprise best selling original, one of the few games that gives players complete control on how they want to build their restaurant. 

This repo contains a patch made specifically for the [YoYo Loader](https://github.com/Rinnegatamante/yoyoloader_vita) by [Rinnegatamante](https://github.com/Rinnegatamante).

# Controls
All of the controls on the screen will self-explanatory, except for the L2/R2 buttons.
- L2/R2: Rear Touch

 How to Install
## For the Runner
1. Buy the game on Steam.
2. Create a folder for the game in ``ux0:data/gms/``-
3. Download the `.APK` file.
4. Grab every single file from the game folder on your PC (except for the `.exe` file) and put it in the assets folder of the `.APK`.
5. Drag it to the folder you created on your PS Vita.
6. Open up YoYoLoader and externalize the game's assets by using the `Optimize APK with Asset Externalization` option and follwing this guide by CatoTheYounger: https://gist.github.com/CatoTheYounger97/ddc2dd4ec459212466ea6f9887bc764b. Note, this will take a lot of time, espicially on Texture Externalization.
8. Once you're done, make sure to set `Fake Windows` on in YoYo Loader.
9. Enjoy the game.

## For the Standalone VPK

1. Buy the game on Steam.
2. Create a folder for the game in ``ux0:data/gms/`` called `CSD2VITA0`.
3. Download the .APK file.
4. Download the `.VPK` file and install it.
5. Grab every single file from the game folder on your PC (except for the `.exe` file) and put it in the assets folder of the `.APK`.
6. Drag it to the folder you created on your PS Vita.
7. Open up YoYoLoader and externalize the game's assets by using the `Optimize APK with Asset Externalization` option and follwing this guide by CatoTheYounger: https://gist.github.com/CatoTheYounger97/ddc2dd4ec459212466ea6f9887bc764b. Note, this will take a lot of time, espicially on Texture Externalization.
8. Once you're done, replace the `game.apk` from `ux0:app/CSD2VITA0` with the `game.apk` file you used to externalize the assets-
9. Enjoy the game.

Note: Don't delete any of the assets folders.

# Issues
The game will run poorly if you set some graphic options to the highest setting. Trying to poke around in the settings menu.
Setting multiple graphic options tot he highest setting will cause textures to not load correctly and therefore will give out a white space.
It's recommended to set everything to the lowest setting for the best performance possible.

# Credits
- [Rinnegatamante](https://github.com/Rinnegatamante) for making the YoYo Loader
- [JohnnyOnFlame](https://github.com/JohnnyonFlame) for making the Externalize All Textures script for UTMT
- [Vertigo Gaming](https://vertigo-games.com) for making the original game
