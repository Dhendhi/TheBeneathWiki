---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mgelft
- monster/cr/1-4
- monster/size/small
- monster/type/beast
statblock: inline
aliases: ["Spiderfrog"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Muk's Guide To Everything He Learned From Tasha p. 33
---
# [Spiderfrog](3-Mechanics\CLI\bestiary\beast/spiderfrog-mgelft.md)
*Source: Muk's Guide To Everything He Learned From Tasha p. 33*  

Spiderfrogs are unique to the Dankwood and may or may not have been created by the eccentric gnome wizard, Doonwaggle. Either way, their high-pitched squeaking sounds indicate that they are thriving in large numbers, despite being difficult to catch.

If you are lucky enough to come across an abandoned spiderfrog egg, raising one kindly will gift you the most helpful house-mate. Spiderfrogs are excellent at getting rid of pests and neatly pack away their webs at night, as they prefer to sleep under the shelter of a big, juicy leaf.

```statblock
"name": "Spiderfrog (MGELFT)"
"size": "Small"
"type": "beast"
"alignment": "chaotic sticky"
"ac": !!int "13"
"hp": !!int "13"
"hit_dice": "2d8 + 4"
"stats":
- !!int "10"
- !!int "16"
- !!int "14"
- !!int "3"
- !!int "12"
- !!int "4"
"speed": "30 ft., climb 30 ft."
"skillsaves":
  "Stealth": !!int "7"
  "Perception": !!int "3"
"senses": "blindsight 10 ft., darkvision 60 ft., passive Perception 13"
"languages": ""
"cr": "1/4"
"traits":
- "desc": "The spiderfrog can breathe air and water."
  "name": "Amphibious"
- "desc": "The spiderfrog can climb difficult surfaces, including upside down on ceilings,\
    \ without needing to make an ability check."
  "name": "Spider Climb"
- "desc": "Spiderfrog's long jump is up to 20 feet and its high jump is up to 10 feet,\
    \ with or without a running start."
  "name": "Standing Leap"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 4 (1d6\
    \ + 1) piercing damage. Target is [grappled](/3-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 11). Until this grapple ends, the target is [restrained](/3-Mechanics/CLI/rules/conditions.md#restrained),\
    \ and spiderfrog can't bite another target."
  "name": "Bite"
"source":
- "MGELFT"
"image": "/3-Mechanics/CLI/bestiary/beast/token/spiderfrog.png"
```
^statblock

```encounter-table
name: Spiderfrog
creatures:
 - 1: Spiderfrog
```