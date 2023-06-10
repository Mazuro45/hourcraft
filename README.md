# Hourcraft [Minecraft Version 1.20]
Hourcraft is an Minecraft Adventure Map based on Hourglass, most Gamplay are the same but it is not an 1 to 1 recreation, the Storyplot is different and I also implemnted own Ideas for Gameplay features. Please read the Full Introductions carefully.  
>
## Cyberwave
- all rights to Hourglass belongs to Cyberwave, this is just a fanart version made in Minecraft.
- https://store.steampowered.com/app/1212410/Hourglass/
- https://twitter.com/cyberwavegames?lang=de
>
## -- Used APIs --
Used code from other Github Users.
>
#### Player Motion API
- https://github.com/BigPapi13/Delta
>
#### WASD Tracking API
- https://github.com/JDawgtor/WASD-Detection
>
>
## -- Installation --
#### In the Downloaded ZIB you will find a File called `Hourcraft_RP` and `Hourglass [Minecraft Edition]`,
>
- The first is the `resourcepack`, put this in your `resourcepacks` folder of your `.minecraft` instance.
- The second file is the `Wolrd`, put this in your `saves` folder of your `.minecraft` instance.
>
## -- Recommendations and Tested Versions --
### Tested Minecraft Version 1.20
- Tested Fabic Mods/Version
- - Fabric 0.14.20
- - sodium-fabric-mc1.20-0.4.10+build.27
- - iris-mc1.20-1.6.4
>
#### External Shaders are supported, but the blend between the internal shaderstate on/off is different, becaused it used another method to applay the shader:
```mcfunction
## Shader appymend Method
trigger toggel.external.shader set #value

## values Description                                                                     Recommendations       Performance Impact
# -1 --> No Internal Shader be used. Overlay will be used. Supports External Shaders.     --- Recommended       --- [Low]
#  0 --> Map Internal Shaders are used. Disable your external Shaders. Fabulous! Needed.  --- Recommended       --- [Madium]
#  1 --> External Shader can be used. Map internal Shaders are enabled.                   --- Recommended       --- [High]
```
### Tested Systems
- Micosoft Windows 10/11
- Linux

## -- Fixes --
In some cases the map can start to Laag, a quick relog in the World can fix it.
Models that are not loaded correctly can be fixt, by using 
```mcfunction
trigger reload
```
## -- Debug Mode --
```mcfunction
trigger start_game ##toggels the custom gamemode
```

