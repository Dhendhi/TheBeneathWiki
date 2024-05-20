---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/tce
- monster/cr/
- monster/size/large
- monster/type/celestial
statblock: inline
aliases: ["Celestial Spirit (7th-level Spell)"]
NoteIcon: monster
BestiaryType: celestial
SourceType: Bestiary
BookSource: Tasha's Cauldron of Everything p. 110
---
# [Celestial Spirit (7th-level Spell)](3-Mechanics\CLI\bestiary\celestial/celestial-spirit-7th-level-spell-tce.md)
*Source: Tasha's Cauldron of Everything p. 110*  

```statblock
"name": "Celestial Spirit (7th-level Spell) (TCE)"
"size": "Large"
"type": "celestial"
"alignment": "Unaligned"
"ac": !!int "18"
"hp": !!int "60"
"stats":
- !!int "16"
- !!int "14"
- !!int "16"
- !!int "10"
- !!int "14"
- !!int "16"
"speed": "30 ft., fly 40 ft."
"damage_resistances": "radiant"
"condition_immunities": "[charmed](/3-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [frightened](/3-Mechanics/CLI/rules/conditions.md#frightened)"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Celestial, understands the languages you speak"
"actions":
- "desc": "The celestial makes a number of attacks equal to half this spell's level\
    \ (rounded down)."
  "name": "Multiattack"
- "desc": "Ranged Weapon Attack: the summoner's spell attack modifier to hit, range\
    \ 150/600 ft., one target. Hit: 2d6 + 2 + summonSpellLevel radiant damage."
  "name": "Radiant Bow (Avenger Only)"
- "desc": "Melee Weapon Attack: the summoner's spell attack modifier to hit, reach\
    \ 5 ft., one target. Hit: 1d10 + 3 + summonSpellLevel radiant damage, and\
    \ the celestial can choose itself or another creature it can see within 10 feet\
    \ of the target. The chosen creature gains 1d10 temporary hit points."
  "name": "Radiant Mace (Defender Only)"
- "desc": "The celestial touches another creature. The target magically regains hit\
    \ points equal to 2d8 + summonSpellLevel."
  "name": "Healing Touch (1/Day)"
"source":
- "TCE"
"image": "/3-Mechanics/CLI/bestiary/celestial/token/celestial-spirit.png"
```
^statblock

```encounter-table
name: Celestial Spirit (7th-level Spell)
creatures:
 - 1: Celestial Spirit (7th-level Spell)
```