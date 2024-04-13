---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/scc
- monster/cr/0
- monster/size/tiny
- monster/type/construct
statblock: inline
aliases: ["Scufflecup Teacup"]
NoteIcon: monster
BestiaryType: construct
SourceType: Bestiary
BookSource: Strixhaven: A Curriculum of Chaos p. 159
---
# [Scufflecup Teacup](3-Mechanics\CLI\bestiary\construct/scufflecup-teacup-scc.md)
*Source: Strixhaven: A Curriculum of Chaos p. 159*  

Scufflecup is a game students created after finding a box of teacups in a nearby building's storage room. The students discovered that pouring hot tea into the cups animates them for 10 minutes and causes them to sprout little arms and legs.

```statblock
"name": "Scufflecup Teacup (SCC)"
"size": "Tiny"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "5"
"hit_dice": "2d4"
"stats":
- !!int "4"
- !!int "14"
- !!int "10"
- !!int "3"
- !!int "3"
- !!int "1"
"speed": "20 ft."
"damage_immunities": "poison"
"condition_immunities": "[blinded](/3-Mechanics/CLI/rules/conditions.md#blinded),\
  \ [exhaustion](/3-Mechanics/CLI/rules/conditions.md#exhaustion), [poisoned](/3-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "blindsight 30 ft. (blind beyond this radius), passive Perception 6"
"languages": ""
"cr": "0"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 3 (1d3\
    \ + 2) bludgeoning damage."
  "name": "Slam"
"source":
- "SCC"
"image": "/3-Mechanics/CLI/bestiary/construct/token/scufflecup-teacup.png"
```
^statblock

```encounter-table
name: Scufflecup Teacup
creatures:
 - 1: Scufflecup Teacup
```