# MyAnimalSetup
Work in progress, being updated pretty regularly right now.
HUGE thanks to the creators of the mods RealisticLivestock and AnimalPackage_vanillaEdition. 
https://github.com/Arrow-kb/FS25_RealisticLivestock
https://www.farming-simulator.com/mod.php?mod_id=333997&title=fs2025



This is just a collection of files from there for a unified animal package to move around my saves. I've started modifying the i3d models provided in AnimalPackage to work with realisticLivestock (ear tags, bumIds, markers, monitors), thus why I don't simply reference those FS25_ mod directories. That would've been much easier.

I don't have a modDesc or icon for this, maybe tomorrow.


### Known Issues

Hereford's are still RL models, haven't moved the bull yet.
Bulls that have RL markings (marker, bumID, even the monitor) have them attached to the base spine, not a hip. So they float around. I've been editing XMLs by hand/with python, this might be something I need to download blender for? I've got a few minutes worth of experience with 3d model stuff, so... give me a bit to work those bugs out. Would gladly accept a PR, just the same.





This change may impact existing animals, especially modded ones.
It's best to do this with a fresh game on a map with default animals. 


## Installation Instructions

Super simple.

Extract this repo in your mods folder, I used a directory called MyAnimals.
( ie, this file should exist: C:\Users\Username\Documents\My Games\FarmingSimulator2025\mods\MyAnimals\realisticAnimals.xml )

Drop rlSettings.xml into your save game directory if one already exists. Make sure that points to the realisticLivestock.xml file in the new directory.

Boot into your save, and you'll have animals!


You can also set the path to realisticLivestock.xml via the in-game Realistic Livestock Settings section, but requires a restart of your save after setting the config. By dropping the file, RL will load these animals on first boot.


