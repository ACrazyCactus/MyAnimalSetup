# MyBergmannAnimalSetup


These are the files I'm using for my animals on Hoff Bergmann. I really enjoy Realistic Livestock, would like visual male/female variations, and like the tags/markings that RealisticLivestock brings to the table. As you know may or may not know, Hoff Bergmann brings it's own animal definitions, while realistic livestock uses the basegame definitions. I discovered that when you start playing in this area, the "animalAnimationIndex" value can get skewered, causing weird anomolies (like midget cows, or chickabbits)

I've addressed this in my game by bringing the specific models, subtypes, and animations that I want to use in my game, directly to the Hof Bergmann map. It's ugly, and not how I planned to 'release' any of it, but I'm throwing it out there now so others can at least get going. I've still got some work to do regarding bull models and aligning their nodes, but as of the first commit, I do have RL eartags on Animal Package_vanillaEdition boar models. 

Chickens, Pigs, and Cow types have been imported, although cows are not using male models yet. I haven't made it around to sheep yet. I did add a "Boy Goose" to the game, for that one GH Issue ;)

The files go into the Hof Bergmann map directory, fillTypes.xml goes into configs, the translation file goes into translations (Sorry, I only speak english), and character goes there.

realisticLivestock.xml goes in the Hof Bergmann directory.
In Settings, under Realistic Livestock, locate this realisticLivestock.xml file and select it. Restart your game, open settings, and regenerate Animal Seller stock. Check the stock, check out your breeding pairs, etc. 