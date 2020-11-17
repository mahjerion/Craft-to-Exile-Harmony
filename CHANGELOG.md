# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.3.2] - 2020-XX-XX

### Updates
- Added 57 new uniques consisting of weapons, jewelry, and shields.
- Uniques, runewords, and regular affix items (mythic, rare, etc.) have had their stats completely refactored. In short, uniques and runewords received a substantial nerf to damage (defense remains more or less untouched), and affixes have been buffed slightly overall. Before, runewords were powerful and deterministic. I want them to still retain their power but to fall more in line with the scaling of Age of Exile. Some runewords and uniques will be meant for leveling, some will be all-around good, and some will be build enablers. Another one of my goals was to encourage crafting, and in order to do so I had to bring affix items 'up to standards' while bringing the other two down. This is a continuing work in progress - I don't think I'll get it right this time round but hopefully it's one step closer.
- Increased attack scaling of bow skills.
- Increased cooldown of all "basic spells" by 20 ticks.
- Weapons now have a flat critical hit base. For instance, the axe's critical hit base has changed from 4-10% to always 5% (10% at level 50).
- Weapons have had their base critical hit lowered overall. Axes and bows are still kings of critical hit chance, while wands and scepters have very low critical hit chance.
- Sword damage has gone up slightly.
- Spears have been buffed significantly. They have high base damage and armor penetration but low critical hit chance.
- Added new affixes for weapons.
- Heal to spell power stat has been reduced in power. Uniques with this stat still have high values of this stat, but don't offer as much healing power anymore. This is to encourage mixing other items instead of stacking all these uniques that do the same thing.
- Runes have had their values shifted slightly.
- Mobs now scale to level 50 instead of 45.
- Increased XP gain from spawners back to 50% from 33%.
- Reduced favor gain from chests to 25 from 50. This is anticipatory for the next update.
- Increased HP of Ender Dragon, Wither, and Blackstone Golem.
- Deadeye can no longer climb but claustrophobia is 90% less effective.
- Assassins have gone back to the old stealth instead of invisibility and now deal extra damage.

### Fixes
- Disabled Blood Mage perk for temporarily.
- Fixed some localization errors for uniques.
- I accidentally removed Balance of Exile from servers. It's back in.
- Fixed the runewords from last update not actually being possible to make.

## [1.3.1] - 2020-11-11

### Updates
- You now only do 20% of your damage when in PvP. This is common practice with RPG games, otherwise it becomes a "who can hit the other guy first" battle.
- All rarities can now roll sockets. Rare - mythic and uniques can roll a max of 1 socket.
- Rare - mythic can now roll an additional affix. Mythics can have up to 7 affixes!
- The chance of rolling an affix has been increased across the board.
- Antiques and relics have had their chance to roll additional sockets increased.
- Antiques can now have 1-5 sockets instead of 1-3.
- Reduced the drop rate of relics to compensate for change above.
- Major buff to uniques across the board.
- Increased variability of runeword stats. The ceiling is still just as high, but they may roll lower. Some runewords have had their values modified slightly to reflect this change.
- Increased base armor, dodge, and magic shield values from Age of Exile gear.
- Crossbows now have armor penetration at the cost of reduced critical hit chance.
- Bow max base damage roll was increased by about 15%.
- Bows have had their critical hit chance reduced heavily.
- Critical hit chance and damage has been reduced.
- Lowered the base value of almost all elemental spells by about 15-25%.
- Reduced power of spell damage affixes slightly.
- Mobs now scale at a higher rate. That is to say, level 50 mobs will be twice as strong as they currently are.
- Increased EXP curve. As a result, I've bumped up EXP gain by about 33%. Overall, it should still be slower.
- Skeleton vanguards and summoners have been weakened greatly.
- Skeleton vanguards, summoners, endermites, slimes, drowned, and iron golems have all had their EXP reduced.
- Reduced EXP gain from spawners from 50% to 33%. Also increased the rate at which EXP falls off within a chunk from 2% to 3% per mob kill.
- Increased the cost of loot crates.

### Mod Updates
- Updated Lithium, Better Dropped Items.
- Added Anvil Fix.

### Fixes
- Enchanting via the anvil now works properly!

## [1.3.0b] - 2020-11-09

### Mod Updates
- Downgraded Charm and Charmonium.

## [1.3.0] - 2020-11-09

### Updates
- Added TheMeowstardCat's Community Server to the list of default available servers. Thanks for supporting CtE for so long!
- Rebalanced Ascendancy classes.
- Added 6 new runewords catered for mages.
- Rebalanced most runewords. That means moderate buffs to the mod runewords and slight nerfs to my runewords.
- Some unique weapons have been rebalanced similarly.
- Mob affixes have been slightly modified to better reflect their names.
- Increased mob HP at lower rarities.
- Added some new affixes for spellcasters.
- Very slightly increased the power of armor/dodge/magic shield.
- Lowered critical hit values.
- Increased difficulty of The Nether and The End (subsequently, mobs grant more experience in these dimensions now).

### Mod Updates
- Updated Origins, Jumploader. FLAN, HQM, Charmonium, Charm.
- Added Better Ping Display.
- Added XP Storage.
- Removed Numberic Ping.

### Fixes
- Fixed incorrect stat descriptions.
- Fixed Nether dailies.

## [1.2.7] - 2020-11-4

### Updates
- You now retain equipped items on death again.
- Added recipe for spell reset potion.
- Added spell reset potion to a quest reward.
- Death chests are protected for 5 Minecraft days.
- (SERVERS ONLY) Enabled /home command because of how finnicky Waystones are recently on servers. You can have a max of 3 homes.
- Very slightly reduced the power of some weapon runewords.

### Mod Updates
- Updated Xaero's, FLAN.
- Added VanillaDeathChest.
- Removed Gravestones.

### Fixes
- Fixed Engima not working.
- Ender pearl crashes should be resolved.

## [1.2.6c] - 2020-11-2

### Fixes
- You no longer keep inventory on death.

## [1.2.6c] - 2020-11-2

### Updates
- Disabled Allure gravestones.

### Mod Updates
- Updated Age of Exile.
- Re-added Gravestones.
- Removed RpgZ.

### Fixes
- Environmental damage no longer breaks your gear instantly.

## [1.2.6b] - 2020-11-1
### Fixes
- Fixed spell crash.

## [1.2.6] - 2020-11-1

### Updates
- New mob farming system: Azuna's Favor. Accrue favor as you explore and open new chests around the world. Your favor increases your chance to find better, and more items, but decreases for every mob you kill.
- Skills and Talent Tree have been split into separate parts.
- The skill tree has changed again. Please be prepared to drink a reset potion.
- You now gain separate skill and talent points. By level 50, you will have 100 talent points and 20 skill points.
- You now keep your gear and hotbar on death.
- New rarities such as Epic/Mythic!
- Passive Talent Tree is scrollable now.
- Magic and Rare essence no longer exist. New much more obtainable salvage items have taken their place.
- Disabled non-AoE items from dropping. You will no longer find level 40 items after killing a level 1 mob!
- Lowered spawn rate of Summoners during a storm.
- Reduced cost of Spawn Teleport Scrolls.
- Crafted gear has seen a general buff.
- Increased max instability.
- Reduced max damage a player needs to do to get EXP/loot from 50% -> 33%.
- Increased max instability to 2500 from 1000.
- Disabled some conflicting Charm and Allure configurations.
- Spawner mobs provide 50% less experience.
- Cleaned up the REI a bit.
- Lowered max HP of Ender Dragon, Wither, and Blackstone Golem.

### Mod Updates
- Updated Age of Exile, Dungeons of Exile, Repurposed Structures, Illuminations, Fabric Waystones, Charm.
- Removed BackSlot.
- Removed Gravestones - Allure has a built in gravestone mod already.

### Fixes
- Disabled the rope bridge from Campanion.
- Disabled Embur Gel Block - causes crashes.
- Crashes caused by Fabric Waystones should be reduced.

## [1.2.4] - 2020-10-26

### Updates
- Added new spawner profiles to some of the commonly occurring dungeons.
- Turned off automatically being partied on a server. You now must use /team. This was problematic with larger servers where experience would be split so much that no one got anything. /team is enabled by default.
- Made it a little easier to get essence.

### Mod Updates
- Updated Cave Biomes, BYG.
- Downgraded The Bumblezone - was causing issues with Curios slots.
- Removed Inventory Sorter.
- Removed Cardinal Components.

### Fixes
- Fixed Curios slots (rings and necklaces).
- Fixed a bunch of crashes related to Common Expansion: Foodstuffs.
- Some of my previous changes were not applies. This has been corrected.

## [1.2.3b] - 2020-10-22

### Fixes
- Fixed the Assassin and Elementalist not being available.

## [1.2.3] - 2020-10-22

### Updates
- Increased area of effect of Heavy Strike, Cleave, and Ground Slam.
- Increased attack scaling of all physical spells.
- Removed phasing from the Assassin ascendancy.
- Removed some downsides from the Elementalist ascendancy.

### Mod Updates
- Updated The Bumblezone, Xaero's.
- Removed Common Expansion: Foodstuffs - lots of related crashes. Will look for alternative food mod.
- Removed Respawnable Pets - doesn't work when attacking pets is disabled.

### Fixes
- Fixed a netherite-related crash.
- Fixed heavy strike not working.

## [1.2.2c] - 2020-10-21

### Updates
- Reverted back to level cap of 50. It scales better given the current configuration.
- Reduced EXP gain by 25%.
- Reduced monster damage by 25%.
- Increased monster health by 25%.

### Mod Updates
- Updated Common Expansion: Foodstuffs, Illuminations.

## [1.2.2] - 2020-10-20

### Updates
- NOTICE: If your Nether and End dimensions were messed up from updates 1.2.0 to 1.2.2, make a new world using the same seed as your world, then copy and past the new level.dat + level.dat_old into your current world to re-enable The Nether and End.
- Increased max level to 100.
- Added new unique item: Kaom's Heart.
- Reworked The Whispering Fire unique to make spell damage scale with strength.
- Added a new quest in the Overworld.

### Mod Updates
- Updated Illuminations, Where Is It, Adventurez, BackSlot, KubeJS, Repurposed Structures, REI.
- Added Dark Dungeons.
- Added Gunpowder Teleport - better mod.
- Added Gravestones.
- Removed Better Graves.
- Removed MyCommands.

### Fixes
- Fixed a unique item error.
- Fixed summoners being overspawned I think.
- Fixed unique loot box being unobtainable.
- Fixed recipes not using tags when it came to chests.

## [1.2.1] - 2020-10-15

### Updates
- You can no longer spawner farm.
- Buffed Hunting bow skills.
- Added a heal effect to Purifying Fires.
- Reduced mana cost of all spells by about 20%.

### Mod Updates
- Updated Xaero's.
- Added Balance of Exile.

### Fixes
- Fixed sound being disabled upon first installation.
- You no longer start with Arcane Bolt.
- You no longer begin with a newbie gear bag - this is given from the first quest.

## [1.2.0] - 2020-10-14

### Updates
- HQM quests are now available on multiplayer!
- HQM quests have been rewritten. You will probably experience a quest reset on your character.
- No longer need to manually copy/paste your datapacks folder! As a result, I have also removed the prepackaged worlds.
- Added Iron Chests, which provides players with an alternative method of storage! Crafting these chests requires the chest of the previous tier and will use essence. Note: copper and silver chests are currently not available.
- Added new furnaces that are quicker (but not necessarily more efficient).
- Increased maximum claim size limit by double, and doubled the rate at which you earn additional space.
- Reworked the skill tree a bit.
- Added some quests to showcase Fabric Waystones and some new repair kits.
- Charm brings a lot of changes to some vanilla mechanics. Check out their mod page for more information.

### Mod Updates
- Updated Age of Exile, REI, Flan, Xaero's, BackSlot, RPGz, Illuminations, Repurposed Structures, The Bumblezone, Inventory Sorter, BYG, HQM, Disable Custom World Advice.
- Added Fabric Furnaces - adds new tiers of furnaces that can smelt at greater rates.
- Added Fabric Wraith Waystones - new craftable teleportation devices also found in villages!
- Added Iron Chests.
- Added CHAS - craftable horse armor and saddle!
- Added Wolves With Armor - makes the Pathfinder even better.
- Added Charm.
- Added Charmonium.
- Added Creeper Spores.
- Removed Project: Save the Pets!
- Removed MAmbience.
- Removed VillagerFix.

## [1.1.0c] - 2020-09-29

### Fixes
- Turned off auto-veinmining. Didn't realize it would work the way it did. Oops! It's still there, just hold the tilde (`) key to while using the correct tool.
- Fixed non-working Wraeclast save for SP.
- Fixed skills not being given.
- Fixed physical skills not working.
- Fixed icon issue regarding new skills.

## [1.1.0b] - 2020-09-28

### Fixes
- Fixed some datapack errors.

## [1.1.0] - 2020-09-28

### Updates
- New singular skill tree which replaces the existing multiple skill trees. Pick your starting position on the tree. You can now access every element/archetype from any starting position, but it may require some trekking across the skill tree. Currently, each stat is specific to an archetype (melee, spells, ranged). Within each archetype you may have access to different elements. Melee focuses on physical (primary), fire, and nature; spells focuses on arcane + water (primary), thunder, and fire; ranged focuses on physical (primary), nature, and thunder. Divine spells have been spread across the tree. Accessing different "elements" of the tree is possible but gated behind the 15th level.
- Increased area of effect of all skills by 50%, aura skills by 100%.
- Increased projectile speed of all spells by 100%.
- Added new physical damage skills: double strike, cleave, ground slam, flicker strike.
- You now gain 2 skill points per level instead of 1.
- Added /tpa since 1. there are no waystones so getting around is already hard enough, and 2. I don't have TelePass either.
- Added a new unique axe: The Whispering Fire - grants you a new skill "Fire Comet" only obtainable via the item which scales highly with weapon damage.
- Enigma now grants 'Teleport'.
- Enabled vein mining by default (no need to hold key down). You just need to use the right tool.
- Crimson Moons now occur less frequently, and spawn mobs slightly less frequently.
- [Harmony] now comes packaged with a default world called Wraeclast.

### Mod Updates
- Updated Age of Exile, Pet Owner, BYG, Diggus Maximus, Patchouli, Roughly Enough Items, Adventurez, Fabric Chunk Pregenerator, Sleep Vote, Xaero's (no more manual backups), Roughly Enough Items, Dank Storage.
- Added Sodium.
- Added BackSlot.
- Added RPGz - RPG-style looting.
- Added Flan - new claim mod. Use a golden hoe on two corners to generate a claim. Type /flan in the claim to open up the menu. You can claim about 10 chunks.
- Added MyCommands - you can now use /tpa (that's it).
- Added I Am Very Smart.
- Removed Get Off My Lawn.
- Removed Lamb Dynamic Lights.
- Removed IKWID.

### Fixes
- Fixed Crafting More Gear quest detection.

## [1.0.5] - 2020-09-18

### Updates
- New skill tree! Arcane!
- Iron gear and above are now salvagable.

### Mod Updates
- Updated Age of Exile.

### Fixes
- Tooltip bug with Age of Exile should be fixed, and lag should be fixed too.

## [1.0.4b] - 2020-09-17

### Mod Updates
- Updated Age of Exile, Oh The Biomes You'll Go.
- Removed YUNG's Better Caves (it bork).

## [1.0.4] - 2020-09-17

### Updates
- Changed the rune order of Last Wish to prevent conflict.
- Changed runes to be more consistent with their stats. Also changed some runes so we don't have like 6 crit runes.
- Fixed some outrageous stat values on uniques/runewords.

### Mod Updates
- Updated Age of Exile, VillagerFix.
- Added YUNG's Better Caves.
- Added Polymorph.

## Fixes
- Lag upon player joining should be greatly alleviated.

## [1.0.3] - 2020-09-16

### Updates
- Added 5 new runewords: Spirit, Breath of the Dying, Insight, Call to Arms, and Last Wish!
- Buffed various runewords.
- Disabled diamond, emerald, and nether start claim blocks.
- Altered recipe of the first 3 claim blocks and the goggles.
- Improved the rewards of some quests.

### Mod Updates
- Updated Age of Exile, Allure, Xaero's.
- Added Leaf Decay.
- Added Player Roles [server only] - players can now use /team on servers.

### Fixes
- Fixed the cobblestone quest to be detection instead of crafting...
- Golden apples should no longer cause crashes.
- Duplicating tools should be fixed.

## [1.0.2b] - 2020-09-15

### Updates
- Added the Pathfinder ascendancy! The Pathfinder specializes in potion crafting and the taming of animals, but comes with the downside of being vegetarian and having less health.
- Added a quest showcasing respawnable pets item.

### Mod Updates
- Updated Age of Exile.
- Added Pet Owner.
- Added Respawnable Pets.
- Added Project: Save the Pets!

## [1.0.2] - 2020-09-15

### Updates
- Renabled HQM on SP - will continue to monitor and add to server when ready.
- Added a quest for CE: Foodstuffs.
- Disabled skipping stones and grappling hook from Campanion.

### Mod Updates
- Updated Origins, Age of Exile, Chat Heads.
- Added Dungeons of Exile.
- Added Better Weather.
- Added Get Off My Lawn <-- Claims
- Added Wild World.
- Added Common Expansion: Foodstuffs.

### Fixes
- Crafted non-AoE gear can no longer be salvagable.

## [1.0.1] - 2020-09-14

### Updates
- Modified some VillagerFix values.
- Made vein mining/tree chopping require the tool (can't just use hand).
- Temporarily disabled Hardcore Questing Mode mod. It's just too early and they're working on fixes still.

### Fixes
- Fixed some keybind stuff.