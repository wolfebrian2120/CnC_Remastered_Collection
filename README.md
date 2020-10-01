# CnC_Remastered_Collection

In order to apply changes to CnC Tiberian Dawn. Build the solution in visual studio 2019. Copy the TiberainDawn.dll file from the bin/release folder into your working game directory. Overwriting the default .dll file.

# Running
Remastered
The build process will produce TiberianDawn.dll and RedAlert.dll in your build directory. These work as mods for the Remastered Collection.

To manually create a local Remastered mod after launching both games once, head to My Documents/CnCRemastered/CnCRemastered/Mods. You should see Tiberian_Dawn and Red_Alert directories.

Create a mod directory within either game, we'll call it Vanilla. Create a directory inside it called Data.

## Tiberian Dawn
Copy TiberianDawn.dll to the Data directory. Next create a JSON file (a text file) ccmod.json in the mod directory and add the following content:

{
    "name": "Vanilla",
    "description": "",
    "author": "",
    "load_order": 1,
    "version_high": 1,
    "version_low": 0,
    "game_type": "TD"
}
The directory structure should look like this:

My Documents/CnCRemastered/CnCRemastered/Mods/Tiberian_Dawn/Vanilla/Data/TiberianDawn.dll
My Documents/CnCRemastered/CnCRemastered/Mods/Tiberian_Dawn/Vanilla/ccmod.json
You should now see the new mod in the mods list of Tiberian Dawn Remastered.

## Red Alert
Copy RedAlert.dll to the Data directory. Next create a JSON file (a text file) ccmod.json in the mod directory and add the following content:

{
    "name": "Vanilla",
    "description": "",
    "author": "",
    "load_order": 1,
    "version_high": 1,
    "version_low": 0,
    "game_type": "RA"
}
The directory structure should look like this:

My Documents/CnCRemastered/CnCRemastered/Mods/Red_Alert/Vanilla/Data/RedAlert.dll
My Documents/CnCRemastered/CnCRemastered/Mods/Red_Alert/Vanilla/ccmod.json
You should now see the new mod in the mods list of Tiberian Dawn Remastered.