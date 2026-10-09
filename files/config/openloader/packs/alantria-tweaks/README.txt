Alantria pack tweaks (loaded by OpenLoader from config/openloader/packs).

- data/dndorigins/origins/dragon.json: hides the D&D Origins "Dragon" race (and with it the dragon
  subtypes) from the race chooser. Becoming a dragon is only possible at Dragon Survival altars.
  Works together with dragonsurvival-server.toml: start_with_dragon_choice = false and
  allow_dragon_choice_from_inventory = false.

- data/alantria/neoforge/biome_modifier/slu_*.json: SLU (Souls-Like Universe) monsters spawn again where they fit:
  common on their home grounds (about 15% of the monsters in a dark forest, 12% in bamboo, jungles and cherry
  groves, 10% in deserts and badlands, 8-15% on the peaks, 6% in the snow, 3% in deep caves, 5-14% in the Nether),
  some in pairs or small patrols there, and rare in ordinary plains, forests and taiga (1-3%); spawn costs stop them
  crowding into one spot. Bosses, the friendly NPCs and the mimic never spawn naturally.
  Written by DaoAscendant/tools/slu_spawns.py (change the table there and run it again).
  These files only load when Dao Ascendant is installed too: it gives SLU's monsters proper spawn rules (on the
  ground, in the dark, like zombies), which the pack's SLU performance build no longer has, and it caps every mod's
  share of a biome's monsters (daoascendant:balance_spawns).
