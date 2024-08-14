[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

# SUMMARY

CHORD: Is a Comprehensive, Holistic, Overhauled, Realistic, Difficulty mod that provides a thorough, interconnected enhancement to the game, making it more immersive, challenging, and engaging.

Unlike other difficulty mods that only make small config changes or just add small tweaks, this mod seeks to provide a complete overhaul to all the existing items, creatures, and configuration settings that affect the game.

In addition, this mod wants the settings to be flexible, fair, but challenging. Giving a Darksouls-like, modern-day experience. 

## REQUIREMENTS

This mod requires the following mods:
-TSL Restored Content Mod 1.8.6
-High-Level Force Powers (v2 & v2.1)
-Content Pack- Feats and Powers

## INCOMPATIBLE MODS

Any mods that edits 2da files, the .utc creature files, or the .uti item files affected in this mod will be incompatible with this mod.

For mods that add new armor or shield items altogether, for now they probably won't be compatible. But comment or message me and let me know which mod you're wanting to combine with this, and I will add a patch (I play with a ton of mods, new item mods included, so there's a good chance I already have made a patch for my local version).

Mods that would be redundant or clash with this and aren't needed are:
- Formidable Sith Lords
- Unstoppable Lightsaber Damage
- Ultimate Balancing Mod

Incompatible mods:
Anything that adds new content like M4-78 where it edits existing items, monsters, and adds new ones will need to have a patch made. Someone is welcomed to do this if they really care enough, personally I am not a fan of M4-78 so that is why this mod doesn't have built in compatibility. 

These mods won't ruin this mod or cause any crashes, etc. But it will break the very tight system that is carefully put together and planned out for this mod. So, if you start seeing less than ideal balance and integration, you know why!

## HIGHLY RECOMMENDED MODS 

- Improved AI 2.2 (I might add my own custom AI that integrates better and adds more depth, but this is a great mod / solution for now)
- Lonna Vash Mod for TSLRCM (Imho a much better mod than something like m4-78, also makes it so that a gray force user can enter the force cave / tomb where you have the "apathy is death" line. In the default game you need max / very high dark side or light side alignment to enter. So, this mod in combination with mine actually makes a gray force user character a rewarding and viable option)
- v2.0 Ultimate Workbench (TSL Crafting System)
- KOTOR2-Loot-Overhaul (just copy files in tslpatcher folder to override to install)

## IINSTALLATION

Just drag and override all .uti, .utc, and . 2da files in your override folder. For the dialog.tlk and changes.ini file I recommend you add my changes by hand (tedious I know, but I am planning to add a patcher to hopefully solve this in a future update).

## CHANGES OVERVIEW

- This mod changes all the original games armor, robes, armored robes, armor upgrade items, and human shields, as well as some belts, masks, and implants.

- It also modifies all creatures / npcs so they are more challenging. For a good number of common creatures / npcs and unique monsters, bosses, and sub-bosses they have been carefully customized to have unique stats, skills, custom gear and inventory items, and power and feat setups for added challenge. 

- Finally, this mod modifies a large amount of 2da configuration files as well.

## ARMOR, ROBES and ARMORED ROBES LOGIC SUMMARY

In KOTOR 2 the Defense stat has nothing to do with damage reduction, it only determines if an enemies attack hit or misses using a d20 DnD system. For source see: https://strategywiki.org/wiki/Star_Wars_Knights_of_the_Old_Republic_II:_The_Sith_Lords/Combat

Because DEF basically is evasion, it makes no sense that heavy armor makes you essentially move like a gazelle and make you hard to hit. Whereas robes make it to where you basically have little to no dodge-ability and are basically a tank but without the damage reduce that realistically being a tank should provide you.

So, a massive change needs to happen here to fix this problem within the KOTOR 2 game system. 

I made it so that robes give you very high dodge-ability as you would come to expect based on logic and what we see in the movies. Whereas with armor you now have damage immunity properties attached to all armor, and their DEF bonuses and DEX bonuses heavily reduced and rebalanced. This rebalancing applies to not just light, medium, and heavy armor, but also the sub-tiers within those categories.

For instance:
Light Armor includes: 
- class / tier 4 armor
- class / tier 5 armor

Medium Armor includes: 
- class / tier 6 armor
- class / tier 7 armor

Heavy Armor includes: 
- class / tier 8 armor
- class / tier 9 armor

So, the rebalancing even takes into consideration the subcategory ligher and heavier light/medium/heavy armors in these breakdowns so that logically and realistically it makes more sense and gives a more thorough level of customization.

Jedi Armored Robes and Robes also receive their own custom rebalancing that follows a logic trend. In essence, robes provide high dodging, generous bonuses, and increase force/lightsaber damage output, but no damage reduction whatsoever (which can be bad depending on the areas, bosses, and difficulty settings). Robes don't cap the +1 defense bonus you get for every 2 points of DEX, so with this setup you are having to rely on dodging, shields, and brains to avoid taking hits. 

Jedi Armored Robes provide damage reduction, but less than what you'd see in even the lightest traditional light armor. That said, you will get bonuses, damage reduction, and some decent dodge-ability.

Here's a rundown of how the logic plays out in general for armor, robes, etc. (note for special named items there's some intentional variance here, also, depending on the item name and description there might be some custom flavorings added intentionally). 

Armor Mod Logic:

Heavy = 65%-70% damage immunity resistance, Def = -11 to -12 (negative def modifier and MAX DEX DEF bonus = 0, usually will result in lowering DEF from this modifier, heavy armor by default gives 8-9 DEF, so this fixes that)

Medium = 57.5%-60% damage immunity resistance, Def = - 6 to -7 (0 or 1, if no custom DEF bonuses and MAX DEX DEF bonus = 0 to 1)

Light = 45%-50% damage immunity resistance, Def = - 2-3 (should only be 2 if no custom item bonuses and MAX DEX DEF bonus = 2 unless other bonuses)

Robes / Clothes = 0% damage immunity resistance, DEF 13-15, lots of other bonuses (especially attribute bonuses, more force damage/power, and more force recovery)

Jedi Armor = DEF + 7-9, and 35% to 40% damage immunity resistance + other bonuses (but less than what robes would provide, unless it's a rare armored robe and you're comparing to like a Padawan robe)

Droid Armor (generally follows a similar system as the light to heavy armors above, with some realism tweaks like being more resilient to fire and elemental damage like cold and sonic, but more vulnerable to elements like ion and electrical damage). In general, droids aren’t really supposed to move like gazelles, and heavy and assault armor will provide better results with party members like HK-47. 

######## OTHER CHANGES ########
- shields now are 1.5x stronger across the board and have 10 charges instead of 5, feats and give an addition 1.6x strength boost.

﻿- Force alignment breakdown:
from forceadjust.2da file:
row  goodcost     evilcost
﻿0    2.25            1 // max evil, 1 to 1 cost or base cost of a given dark/neutral power, 2.25x means over double FP cost for good
1	   2.00	           1
2	   1.75	           1
3	   1.50	           1
4	   1.25	           1
5	   0.85	           0.85     //neutral alignment, since no attribute bonuses, these characters given a 15% FP reduction for all powers.
6	   1	             1.25
7	   1	             1.50
8	   1	             1.75
9	   1	             2.00
10	 1	             2.25. // max good, ﻿1 to 1 cost or base cost of a given good/neutral power, ﻿2.25x FP cost for dark powers


- All force powers are easily 2x to 4x times more costly. the more broken the power, the most cost. That said, cost is reasonable and calculated, but you won't be spamming all force powers willy nilly unless youre a neutral, gray force user. In general, you will get to spam a high level ability about 4-5 times if using someone like Kreia with a ton of Wisdom


- all companions now gain 90% of the xp you gain, instead of 80% like base game

- all level xp requirements are cut in half. So you can reach level 50 without cheats.

## DIFFICULTY SETTING OPTIONS RECOMMENDATION

Personally, I recommend you play this with a difficulty level between Difficult (3x enemy damage modifier), Very Difficult (3.5x enemy damage modifier), and Overpowering (4x enemy damage modifier).

I personally like Very Difficult to Overpowering, the balance there feels just about right in most cases. 

If you choose to play on Insanity (4.5x enemy damage modifier) or Suicide (5x enemy damage modifier) and you manage to beat the game without cheats, then you will have all bragging rights, and I will be personally impressed.

## FUTURE UPDATES

I plan to add custom patches for other armor mods, as well as continue to refine the creature and item updates, so stay tuned and consider following this mod!

## PERMISSIONS

This mod can be freely used and shared for non-commercial purposes; all I ask is that I am properly credited. So, feel free to make your own patches and mods on top of this one.

## SUPPORT

I poured my heart and soul into this mod. Hundreds of individual files were edited using the KOTOR TOOL. As well as hours thinking about the new, balanced armor system that allowed for rewarding gameplay without making you unstoppable and breaking the immersion this mod seeks to establish. I spent a long time on this, so I hope it brings you enjoyment in your KOTOR 2 game.

All I ask is that if you enjoy this mod that you like it, endorse it, rate it, and tell your friends about it! If you're feeling generous then please star the Github repo for this mod and consider following me on GitHub.

If you'd like to help me on this modding journey than feel free to reach out. The ultimate goal of this mod is the make the best mod possible and I am happy to share the spotlight. If we can greatly increase KOTOR 2's replayability and make it way more fun than this mod will have accomplished what it set out to do.

NOW GO OUT THERE AND HAVE SOME FUN! And remember... Apathy is death!
