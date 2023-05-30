## Description
By default makes Demisters push mist 2x the vanilla amount. More visibility for the Mistlands. (Warning, modifying multiplier to very high amounts like 10x might chug your computer.)

## Author
All credit belongs to [Toombe](https://www.nexusmods.com/valheim/users/13830595), who created and uploaded the mod (and image) to [NexusMods](https://www.nexusmods.com/valheim/mods/2103).

## Mod Information
Changes the distance that Demisters push Mist away. Defined by a multiplier in a config file, default value is 2x.

At the current stage the mod does it to every Demister in the game, might add options for this later so that you can for example pick only Wisplight to save some performance.

Current Demisters affected in the game, afaik, are: Wisplight, Mistwalker and those orb lanterns that spawn naturally in the Mistlands.

Editing the config while in game currently does not update live, for equippables such as Wisplight and Mistwalker you will need to equip them again for the effect to apply. For structures you will either need to restart the game or leave the area far enough away so that they de-load and get the new config value applied upon reload.

I'll try to make things more user friendly when I figure things out, this is my first ever mod and it's been a long time since I learned the basics of C#. 

Last of all, go have fun :)

### Short guide to modifying the mod config:

Running the game once with the mod installed creates the config file, `toombe.BetterWisplight.cfg`.
You can adjust the config values by editing this file using a text editor or in-game using an in-game config manager.

The number in the config file represents the multiplier amount, by default it's 2 (for 2x the default demisting) but you can change it to a higher amount if you prefer. The value is in float format so decimal values are possible.