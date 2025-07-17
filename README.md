This addon adds a undertale dialog box that you can use with chat commands.

It was a rewrite of this addon here: https://steamcommunity.com/sharedfiles/filedetails/?id=3363203207

here is the steam version of this addon here: https://steamcommunity.com/sharedfiles/filedetails/?id=3514832468

It has all the sounds aswell

it may or may not have an 2 or 3 easter eggs :v

It now has expressions!!!!!

But how do you add your expressions?


Its very simple, make sure your sprite is 52x43, add them all into 1 folder, make sure there is black around the sprite, and make sure your sprite is white aswell, also make sure its .png, now how to add them


1: download the .zip file (below) (to extract it use either 7-zip, or just the default windows explorer)

2: extract the folder to the gmod addons folder (it should look like this: C:\Program Files (x86)\Steam\steamapps\common\GarrysMod\garrysmod)

3: put your sprites into a folder, call it whatever you want

4: put the folder with your sprites in it, in this path: Undertale Dialog Box\materials\db\

5: now after you did that, launch gmod and type this in the console (db_expression)

6: after you did that, type /db "text goes here" (remove the "")

7: congratulations!, your expression should now show!

8: (oh i forgot, make sure you go into the addon's lua folder, this path here: C:\Program Files (x86)\Steam\steamapps\common\GarrysMod\garrysmod\addons\Undertale Dialog Box\lua\autorun)

9: then open this file here (dialog_box.lua)

10: under local Expressions = {} (copy this under it)

AddExpressions(Expressions, "materials/db/foldername here", "characternamehere")

11: after you are done with that, save the file, with ctrl+s, and on number 5 at the top, type that and you are done!


-------------------------------------------------------------------------------------------------------------------------------------------------------





This was a rewrite of this addon here

Huge thanks goes to uzi for rewriting this entire addon from scratch, its true to the original game

anywho here is how you use it:


Usage
/db "text goes here" (without the "")
/db (0.5) "text goes here" - Creates dialog box with set speed and text (default speed 1) (without the brackets, and "")
/db[r]text goes here[/r] - Change the text color in the Dialog Box (there is r,y,b,lb,g,p,o,gd) (replace [r] and, [/r] with any of the colors you would like)


ConVars
db_admin 0/1 - Toggles admin only mode.
db_expression - Toggles the expression menu (you can select your expression from the vgui)


Sans Undertale

Son you really ducked up hard this time, now you will become a can of pringles, said the increased munchies.


(please note this is the github version, to download the .zip, click on it and it will download for you.)
