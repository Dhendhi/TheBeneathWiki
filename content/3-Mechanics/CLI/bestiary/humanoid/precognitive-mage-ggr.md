---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/3
- monster/size/medium
- monster/type/humanoid/any-race
statblock: inline
aliases: ["Precognitive Mage"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Guildmasters' Guide to Ravnica p. 228
---
# [Precognitive Mage](3-Mechanics\CLI\bestiary\humanoid/precognitive-mage-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 228*  

Precognitive mages, a rarity among Azorius spellcasters, are capable of capturing glimpses of the future. They are typically employed to anticipate the actions of wanted criminals, thus aiding in their capture.

```statblock
"name": "Precognitive Mage (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Lawful Neutral"
"ac": !!int "11"
"hp": !!int "63"
"hit_dice": "14d8"
"stats":
- !!int "9"
- !!int "13"
- !!int "10"
- !!int "18"
- !!int "13"
- !!int "11"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "3"
  "Intelligence": !!int "6"
"skillsaves":
  "Perception": !!int "3"
"senses": "truesight 120 ft., passive Perception 13"
"languages": "Common plus any one language"
"cr": "3"
"traits":
- "desc": "The mage's innate spellcasting ability is Intelligence (spell save DC 14).\
    \ It can cast the following spells, requiring no material components:\n\n1/day\
    \ each: [clairvoyance](/3-Mechanics/CLI/spells/clairvoyance.md), [locate object](/3-Mechanics/CLI/spells/locate-object.md)\n\
    \n3/day: [detect thoughts](/3-Mechanics/CLI/spells/detect-thoughts.md), [mage\
    \ armor](/3-Mechanics/CLI/spells/mage-armor.md)"
  "name": "innate"
"actions":
- "desc": "Melee Weapon Attack: +1 to hit, reach 5 ft., one target. Hit: 2 (1d6\
    \ - 1) bludgeoning damage, or 3 (1d8 - 1) bludgeoning damage if used with two\
    \ hands."
  "name": "Quarterstaff"
- "desc": "The mage targets one creature within 120 feet of it that it can see. The\
    \ target takes 18 (4d8) psychic damage, and it must succeed on a DC 14 Intelligence\
    \ saving throw or be [stunned](/3-Mechanics/CLI/rules/conditions.md#stunned) until\
    \ the end of its next turn."
  "name": "Glimpse the Temporal Flood (Recharge 5-6)"
"reactions":
- "desc": "When the mage or a creature it can see makes an attack roll, a saving throw,\
    \ or an ability check, the mage can cause the roll to be made with advantage or\
    \ disadvantage."
  "name": "Precognitive Insight (3/Day)"
"source":
- "GGR"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/precognitive-mage.png"
```
^statblock

```encounter-table
name: Precognitive Mage
creatures:
 - 1: Precognitive Mage
```