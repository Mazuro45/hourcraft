# Hourcraft
Hourglass made in Minecraft
>
## Cyberwave
- all rights to Hourglass belong to Cyberwave, this is just a fanart version made in Minecraft.
- https://store.steampowered.com/app/1212410/Hourglass/
- https://twitter.com/cyberwavegames?lang=de
>
## -- APIs by others --
I also used code form other Github Users.
>
Player Motion API
- https://github.com/BigPapi13/Delta
>
WASD Tracking API
- https://github.com/JDawgtor/WASD-Detection
>
>
## -- Instuctions --
In the Downloaded ZIB you will find a File called `Hourcraft_RP` and `Hourglass [Minecraft Edition]`,
>
- The first is the `resourcepack`, put this in your `resourcepacks` folder of your `.minecraft` instance.
- The scond file ist the `Wolrd`, put this in your `saves` folder of your `.minecraft` instance.
>
## -- Fixes --
In some cases the map can start to Laag, a quick relog in the World can fix it.
Models that are not loaded correctly can be fixt, by using 
```mcfunction
trigger reload
```
## -- Level Editor [Experimental] --
If you want to make your own Levels, you can enter the Level Editor by Clicking at the Level Editor Icon in your inventory after you completing the Tutorial.
Now you have Creative Mode and the abylity to swap in and out of the Playable mode by type: 
```mcfunction
function hg_data:start_test
function hg_data:stop_test
```
### Create a new Level
```mcfunction
# creates a new level and saves the old one
function hg_data:level/create

# saves a level
function hg_data:level/save

# load a level
scoreboard players set hg.level.id #[Number of the level]
function hg_data:level/load
```
you can edit every level at any time, but if you load a level while an another level is loaded, the last level will be saved and unloaded.

### Add/Remove Game Feature
```mcfunction
# load a invetory page
trigger inv_page set #[Number of the page]
```

- 1 --> Game Features
- 2 --> Decorative things

By pressing F when you are holding an Item you can Swap between different States for eample:
Plattform Flat [X-] + F --> Plattform Flat [X+] + F Plattform Flat [Z-] and so one.

Place a Feature were ever you want, but many Types are checking the Blocks for air around.

For deleting a Feature you can brake the Redstone Lamp 2 Blocks under it, or sneak Right Click with an empty Hand on it.


