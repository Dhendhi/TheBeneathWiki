---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/8
- monster/size/large
- monster/type/undead
statblock: inline
aliases: ["Gloamwing"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Guildmasters' Guide to Ravnica p. 215
---
# [Gloamwing](3-Mechanics\CLI\bestiary\undead/gloamwing-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 215*  

A gloamwing's head is almost ratlike, with prominent teeth, and its leathery skin is stretched tight over its skull, where its eyes are empty sockets. Its body is mottled with bony plates, and great wings stretch from its shoulders.

```statblock
"name": "Gloamwing (GGR)"
"size": "Large"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "16"
"hp": !!int "136"
"hit_dice": "16d10 + 48"
"stats":
- !!int "20"
- !!int "16"
- !!int "17"
- !!int "2"
- !!int "11"
- !!int "6"
"speed": "30 ft., fly 60 ft."
"saves":
  "Dexterity": !!int "6"
  "Strength": !!int "8"
"skillsaves":
  "Stealth": !!int "6"
  "Perception": !!int "3"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/3-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/3-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [poisoned](/3-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 120 ft., passive Perception 13"
"languages": "understands Common"
"cr": "8"
"traits":
- "desc": "If its specter rider is reduced to 0 hit points, the gloamwing is destroyed."
  "name": "Death Link"
- "desc": "The gloamwing doesn't provoke an opportunity attack when it flies out of\
    \ an enemy's reach."
  "name": "Flyby"
- "desc": "While in sunlight, the gloamwing has disadvantage on attack rolls, as well\
    \ as on Wisdom (Perception) checks that rely on sight."
  "name": "Sunlight Sensitivity"
"actions":
- "desc": "The gloamwing makes two attacks: one with its bite and one with its claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 18 (3d8\
    \ + 5) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 15 (3d6\
    \ + 5) slashing damage."
  "name": "Claws"
"source":
- "GGR"
"image": "/3-Mechanics/CLI/bestiary/undead/token/gloamwing.png"
```
^statblock

```encounter-table
name: Gloamwing
creatures:
 - 1: Gloamwing
```