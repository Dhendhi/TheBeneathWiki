---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tce
- monster/cr/
- monster/size/medium
- monster/type/beast
statblock: inline
aliases: ["Beast of the Land"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Tasha's Cauldron of Everything p. 61
---
# [Beast of the Land](3-Mechanics\CLI\bestiary\beast/beast-of-the-land-tce.md)
*Source: Tasha's Cauldron of Everything p. 61*  

```statblock
"name": "Beast of the Land (TCE)"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"stats":
- !!int "14"
- !!int "14"
- !!int "15"
- !!int "8"
- !!int "14"
- !!int "11"
"speed": "40 ft., climb 40 ft."
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "understands the languages you speak"
"traits":
- "desc": "If the beast moves at least 20 feet straight toward a target and then hits\
    \ it with a maul attack on the same turn, the target takes an extra 1d6 slashing\
    \ damage. If the target is a creature, it must succeed on a Strength saving throw\
    \ against your spell save DC or be knocked [prone](/3-Mechanics/CLI/rules/conditions.md#prone)."
  "name": "Charge"
- "desc": "You can add your proficiency bonus to any ability check or saving throw\
    \ that the beast makes."
  "name": "Primal Bond"
"actions":
- "desc": "Melee Weapon Attack: the summoner's spell attack modifier to hit, reach\
    \ 5 ft., one target. Hit: 1d8 + 2 + PB slashing damage."
  "name": "Maul"
"source":
- "TCE"
"image": "/3-Mechanics/CLI/bestiary/beast/token/beast-of-the-land.png"
```
^statblock

```encounter-table
name: Beast of the Land
creatures:
 - 1: Beast of the Land
```