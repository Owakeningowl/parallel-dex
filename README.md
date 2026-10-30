# Parallel Dex

A Pokédex for Pokémon Parallel Emerald v1.2 in Pokémon Null's dex layout (the Porydex / Showdown dex front-end):
every Pokémon's stats, types, abilities, evolutions and learnsets, every move and ability, and the wild encounters per
location.

Live: https://owakeningowl.github.io/parallel-dex/

Data:
- species, abilities, evolutions, level-up and TM / tutor learnsets: the game's raw species data from Joggel's
  Parallel Emerald Drive folder;
- move power, type, accuracy, PP, priority and category: read from the game ROM itself, with Joggel's notes on each
  changed move in its description; the game's own moves (Bubble Smack, Poisonous Graze, Flaring Rush, Tectonic Drift)
  use the ROM's descriptions;
- ability, item and type chart changes: Joggel's "Changes to Pokémon and the Battle System" sheet;
- wild encounters: Joggel's "Encounters and Dex" sheet (wild levels follow your highest-level Pokémon, so only rates
  are shown);
- move / ability / item descriptions otherwise from Pokémon Showdown.
