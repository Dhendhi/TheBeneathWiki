---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/7
- monster/size/medium
- monster/type/humanoid/any-race
statblock: inline
aliases: ["Druid of the Old Ways"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Guildmasters' Guide to Ravnica p. 239
---
# [Druid of the Old Ways](3-Mechanics\CLI\bestiary\humanoid/druid-of-the-old-ways-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 239*  

The druids of the Old Ways are the keepers of ancient Gruul traditions devoted to the primal ferocity of animal gods such as Ilharg the Raze-Boar and Kashath the Stalker.

## The End-Raze

The druids of the Old Ways believe that civilization will never be eradicated by scattered raids and petty skirmishes. They cling to the idea of a coming apocalypse, the End-Raze, when Ilharg's hoofs will trample every brick and stone of Ravnica's soaring skylines to rubble. The world will return to a state of nature in which the lawless code of muscle and savagery will reign once again.

```statblock
"name": "Druid of the Old Ways (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Chaotic Neutral"
"ac": !!int "14"
"hp": !!int "90"
"hit_dice": "12d8 + 36"
"stats":
- !!int "11"
- !!int "15"
- !!int "16"
- !!int "10"
- !!int "20"
- !!int "14"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "5"
  "Wisdom": !!int "8"
  "Constitution": !!int "6"
"skillsaves":
  "Nature": !!int "3"
  "Perception": !!int "8"
  "Survival": !!int "8"
"senses": "passive Perception 18"
"languages": "Common, Druidic"
"cr": "7"
"traits":
- "desc": "The druid is a 12th-level Gruul spellcaster. Its spellcasting ability is\
    \ Wisdom (spell save DC 16, +8 to hit with spell attacks). It has the following\
    \ druid spells prepared:\n\nCantrips (at will): [druidcraft](/3-Mechanics/CLI/spells/druidcraft.md),\
    \ [produce flame](/3-Mechanics/CLI/spells/produce-flame.md), [resistance](/3-Mechanics/CLI/spells/resistance.md),\
    \ [thorn whip](/3-Mechanics/CLI/spells/thorn-whip.md)\n\n1st level (4 slots):\
    \ [cure wounds](/3-Mechanics/CLI/spells/cure-wounds.md), [faerie fire](/3-Mechanics/CLI/spells/faerie-fire.md),\
    \ [thunderwave](/3-Mechanics/CLI/spells/thunderwave.md)\n\n2nd level (3 slots):\
    \ [beast sense](/3-Mechanics/CLI/spells/beast-sense.md), [flame blade](/3-Mechanics/CLI/spells/flame-blade.md),\
    \ [pass without trace](/3-Mechanics/CLI/spells/pass-without-trace.md)\n\n3rd\
    \ level (3 slots): [conjure animals](/3-Mechanics/CLI/spells/conjure-animals.md),\
    \ [dispel magic](/3-Mechanics/CLI/spells/dispel-magic.md), [plant growth](/3-Mechanics/CLI/spells/plant-growth.md)\n\
    \n4th level (3 slots): [dominate beast](/3-Mechanics/CLI/spells/dominate-beast.md),\
    \ [freedom of movement](/3-Mechanics/CLI/spells/freedom-of-movement.md), [wall\
    \ of fire](/3-Mechanics/CLI/spells/wall-of-fire.md)\n\n5th level (2 slots):\
    \ [commune with nature](/3-Mechanics/CLI/spells/commune-with-nature.md), [conjure\
    \ elemental](/3-Mechanics/CLI/spells/conjure-elemental.md), [scrying](/3-Mechanics/CLI/spells/scrying.md)\n\
    \n6th level (1 slots): [transport via plants](/3-Mechanics/CLI/spells/transport-via-plants.md),\
    \ [wall of thorns](/3-Mechanics/CLI/spells/wall-of-thorns.md)"
  "name": "spells"
- "desc": "The druid deals double damage to objects and structures."
  "name": "Siege Monster"
- "desc": "The druid can communicate with beasts and plants as if they shared a language."
  "name": "Speak with Beasts and Plants"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 3 (1d6)\
    \ bludgeoning damage, or 4 (1d8) bludgeoning damage if used with two hands."
  "name": "Quarterstaff"
"source":
- "GGR"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/druid-of-the-old-ways.png"
```
^statblock

```encounter-table
name: Druid of the Old Ways
creatures:
 - 1: Druid of the Old Ways
```