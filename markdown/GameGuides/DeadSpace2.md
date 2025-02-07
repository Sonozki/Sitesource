![Dead Space 2](../Images/DeadSpace2_header.png "Shot by Jim2point0"){.shadowed .autosize}

## Summary

Feature | Supported
--|--
Vanilla Photo Mode | No
Hotsampling | Yes
DSR | Yes
Custom Aspect Ratios | Yes
Reshade | Yes 
Ansel | No
Graphics API | 9

Resolution can be changed in configuration file. GeDoSaTo is supported according to [whitelist](https://github.com/PeterTh/gedosato/blob/master/pack/config/whitelist.txt#L52). 
Configuration is similar to [DS1.](https://steamcommunity.com/sharedfiles/filedetails/?id=604010024) 

## [Cheat Table](../CheatTables/DeadSpace2_camera.CT) Features:

### Relative Camera Control (RCC)
Control the camera position, relative to player. Limited by walls. 

Description:

- `FOV`: Field of View.
- `Zoom` (Cam Distance): how far back the camera sits from character. The further you go, the smaller char is. 

- `Cam Height`: by increasing\decreasing this, the camera will move up\down. HOWEVER, this does not apply when looking up or down - change distance for this.

- `Center Offsets`: 3 values the game uses to determine how far left\right the camera sits from character. However, it's dependent on where you're looking. No matter where you look, these will always move the camera left\right. To make things simple, hotkeys are setup to change all 3 at the same time.

- `Pivot Distance`: The camera rotates around a pivot point. By default, that point is located wherever Isaac is. However, if you increase this value, the camera will rotate around a point in front of Isaac. Negative values for behind him. This is one of several ways to simply put the camera in front of Isaac and get him out of the shot. Has other uses too.

@alert important  
Aiming and many other in-game events reset camera values. To prevent value from changing, **freeze it**: click in the box leftside of it's name. Or highlight it and press `Space`.  
@end

Hotkeys:

Controls|CTRL +
--|--
Zoom|Num +/-
Height|Num 2/8
X|Num 4/6
Y|Num 3/9
Char Size|PgUp/Dn

Technical info: 

This is the port of Jim2Point0's DS1 table. See [original description.](https://web.archive.org/web/20141021190640/flickr.com/groups/deadendthrills/discuss/72157631765632995/) Altho code differs, the same camera values with similar structure were found using CE's 'Group search'. The table only modifies values, without changes to code.

### Free Camera
Detaches camera from character. 

Control your camera by modifying 3 values. In-game rotating still works and you still control the character. 

Controls|ALT +
--|--
Toggle|Num 0
Height|Num 2/8
X|Num 4/6
Y|Num +/-

Controls are not handy, as they move camera in absolute coordinate system. Recommended to use after RCC.

Credits: [Notes by GhostInTheCamera.](https://github.com/ghostinthecamera/PhotomodeCheatTables/blob/master/WIP/Dead%20Space%202/notes.txt)

### Extra

- Timescale

Timescale is game speed multiplier. 1.00 - default, >1 faster, 0 (and lower) pauses the game, while still able to control the camera. 

Controls|CTRL +
--|--
Timefreeze|0
Timescale|7/8

- Enemies don't see you.
- 0g anywhere (Ctrl+9)

## Common Info

**Easing attaching to process**  
In settings, set auto-attach to `deadspace2.exe` or `dead` for short and tick `Even`.  
Alternatively, set and use hotkey `Attach to current foreground process`.  
Otherwise, use script `Attach to game` or do it manually.

Change the selected value by pressing `Enter` or double clicking on it.

Customize hotkeys and their functions by pressing `Ctrl+H` on selected entry. Hotkeys work even if game window is minimized, so it's better to use unusual combinations.

## Useful Links

- [PC Gaming Wiki](https://www.pcgamingwiki.com/wiki/Dead_Space_2)
- [SweetFX](https://sfx.thelazy.net/games/game/30/)
