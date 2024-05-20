---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/1-2
- monster/size/medium
- monster/type/humanoid/kraul
statblock: inline
aliases: ["Kraul Warrior"]
NoteIcon: monster
BestiaryType: humanoid (kraul)
SourceType: Bestiary
BookSource: Guildmasters' Guide to Ravnica p. 213
---
# [Kraul Warrior](3-Mechanics\CLI\bestiary\humanoid/kraul-warrior-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 213*  

Kraul society is organized into well-defined roles and castes. The vast majority of the kraul occupy various tiers of soldiery, from commanders and elite troops down to the lowliest infantry.

## Kraul

The kraul are an ascendant power group within the Golgari Swarm, long content to linger at the margins of the undercity but now increasingly making their buzzing voices heard in the subterranean Golgari guildhall. These six-legged, insectile beings are hard-headed and literal-minded, with little grasp of metaphor or nuance.

```statblock
"name": "Kraul Warrior (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "kraul"
"alignment": "Neutral Evil"
"ac": !!int "18"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"stats":
- !!int "15"
- !!int "12"
- !!int "13"
- !!int "10"
- !!int "11"
- !!int "8"
"speed": "30 ft., climb 30 ft."
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "Kraul, understands Common but can't speak it"
"cr": "1/2"
"traits":
- "desc": "The kraul is immune to the [charmed](/3-Mechanics/CLI/rules/conditions.md#charmed)\
    \ and [frightened](/3-Mechanics/CLI/rules/conditions.md#frightened) conditions\
    \ while within 30 feet of at least one other kraul."
  "name": "Hive Mind"
- "desc": "The kraul has advantage on an attack roll against a creature if at least\
    \ one of the kraul's allies is within 5 feet of the creature and the ally isn't\
    \ [incapacitated](/3-Mechanics/CLI/rules/conditions.md#incapacitated)."
  "name": "Pack Tactics"
- "desc": "The kraul can climb difficult surfaces, including upside down on ceilings,\
    \ without needing to make an ability check."
  "name": "Spider Climb"
"actions":
- "desc": "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 5 (1d6 + 2) piercing damage, or 6 (1d8 + 2) piercing\
    \ damage if used with two hands to make a melee attack."
  "name": "Spear"
"source":
- "GGR"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/kraul-warrior.png"
```
^statblock

```encounter-table
name: Kraul Warrior
creatures:
 - 1: Kraul Warrior
```