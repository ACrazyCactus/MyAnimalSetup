# MyBergmannAnimalSetup
Work in progress, being updated pretty regularly right now.

These are the files I'm using for my animals on Hoff Bergmann. I take no credit for the models, even if I may have edited them a bit from the originals to make them work with my particular setup.

Chickens, Pigs, and Cow types have been imported. I haven't made it around to sheep yet. I did add a "Boy Goose" to the game, for that one GH Issue ;)

The files go into the Hof Bergmann map directory, fillTypes.xml goes into configs, the translation file goes into translations (Sorry, I only speak english), and character goes there.

realisticLivestock.xml goes in the Hof Bergmann directory.

Start a new save with all of your mods, but WITHOUT realistic livestock. Save the game. Open your savegame directory, and create rlSettings.xml
```
<?xml version="1.0" encoding="utf-8" standalone="no"?>
<settings>
    <foodScale value="1"/>
    <diseasesChance value="3"/>
    <maxNumMessages value="1"/>
    <accidentsChance value="5"/>
    <useCustomAnimals value="2" path="C:/Users/{USERNAME}/Documents/My Games/FarmingSimulator2025/mods/FS25_HofBergmann/realisticLivestock.xml"/>
    <diseasesEnabled value="2"/>
    <maxDealerAnimals value="19"/>
    <deathEnabled value="2"/>
</settings>
```
Save this file, and restart your game.
Because the RL mod overrides your animals.xml, and hoffman doesn't IMPORT NEW ANIMALS, it overrides the full base animal list, you will lose ducks/rabbits/geese/cats, as well as a misalignment in the visualAnimalIndex mappings when you start a new Bergmann map with RL enabled.
By loading the override on the first boot of the save with the RL mod, you will avoid the rabbit hutch and goose husbandry disappearing from your placeables.xml. (although they can be restored by copying them from the placeables.xml of a base bergmann save file)

In Settings, under Realistic Livestock, locate this realisticLivestock.xml file and select it. Restart your game, open settings, and regenerate Animal Seller stock. Check the stock, check out your breeding pairs, etc. 

