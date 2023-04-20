# Hourcraft
Hourcraft is an Minecraft Adventure Map based on Hourglass, most Gamplay are the same but it is not an 1 to 1 recreation, the Storyplot is different and I also implemnted own Ideas for Gameplay features. Please read the Full Introductions carefully.  
>
## Cyberwave
- all rights to Hourglass belong to Cyberwave, this is just a fanart version made in Minecraft.
- https://store.steampowered.com/app/1212410/Hourglass/
- https://twitter.com/cyberwavegames?lang=de
>
## -- Used APIs --
I also used code form other Github Users.
>
#### Player Motion API
- https://github.com/BigPapi13/Delta
>
#### WASD Tracking API
- https://github.com/JDawgtor/WASD-Detection
>
>
## -- Installation --
In the Downloaded ZIB you will find a File called `Hourcraft_RP` and `Hourglass [Minecraft Edition]`,
>
- The first is the `resourcepack`, put this in your `resourcepacks` folder of your `.minecraft` instance.
- The second file is the `Wolrd`, put this in your `saves` folder of your `.minecraft` instance.
>
## -- Recommendations --
- Tested Minecraft Version 1.19.4.
- Tested Fabic Mods/Version
- - Fabric 0.14.17
- - sodium-fabric-mc1.19.4-0.4.10+build.24
#### External Shaders are not supported yet, if you still want to use an external shader, use:
```mcfunction
trigger toggel.external.shader set #value

## values
# 0 --> External Shader can be used. Map internal Shaders disabled.   --- Not Recommended
# 1 --> Map Internal Shaders are used. Disable your extermal Shaders. --- Recommended

```
## -- Fixes --
In some cases the map can start to Laag, a quick relog in the World can fix it.
Models that are not loaded correctly can be fixt, by using 
```mcfunction
trigger reload
```

