# S1X-Grapple-Mod
A mod for s1x that allows the Advanced Warfare grapple hook from the grapple playlist to work on all maps. (**nomrally locked to dlc 2-4**)

You'll meed the latest version of s1-mod https://alterware.dev make sure you run the alterware launcher so it installs the necessary files
and you will also need the exe given with the download in the releases section.

inside the **s1x_grapple_mod.rar** drag both the **grapple.ff** and the **s1-mod** exe into the AW directory (If you have a zone folder just place the **grapple.ff** inside there)

Assuming it will be mostly trickshotters using this, i have created a gsc scipt with fast last bind (prone, aim and knife) **place the scripts folder in a folder called s1 (s1/scripts/grapple.gsc) and just drag and drop the data folder into the game directory**

Once on the game, type **loadzone grapple** into the dev console and you'll likely see it remove the textures on you player model (that just happens whenever a mod is loaded)

# How To Get The Grapple To Actually Work
Unfortunately it's a bit broken when selecting a class

How i'm getting it to work is loading whatever map u want, spawn in and in the dev console enter the command **scr_game_grappling_hook 1** (0 = disabled, 1 = enabled) you then want to **map_restart** and when it reloads it wont let you pick ur class, change the **scr_game_grappling_hook 1** to **0** then go to choose your class, then before selecting a class, change the **scr_game_grappling_hook** command back to a **1** and then select the class you want.

Then you are good to go, sometimes after this you can change class through out the game although alot of the time you'll have to change the dvar to a 0 to open the class menu then change it back to a 1.

If you are struggling or don't understand feel free to contact me on https://x.com/xreecey with any questions
