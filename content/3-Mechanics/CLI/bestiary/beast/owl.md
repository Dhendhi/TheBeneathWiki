---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mm
- monster/cr/0
- monster/environment/arctic
- monster/environment/forest
- monster/size/tiny
- monster/type/beast
statblock: inline
aliases: ["Owl"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Monster Manual p. 333. Available in the SRD and the Basic Rules.
---
# [Owl](3-Mechanics\CLI\bestiary\beast/owl.md)
*Source: Monster Manual p. 333. Available in the SRD and the Basic Rules.*  

```statblock
"name": "Owl"
"size": "Tiny"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "1"
"hit_dice": "1d4 - 1"
"stats":
- !!int "3"
- !!int "13"
- !!int "8"
- !!int "2"
- !!int "12"
- !!int "7"
"speed": "5 ft., fly 60 ft."
"skillsaves":
  "Stealth": !!int "3"
  "Perception": !!int "3"
"senses": "darkvision 120 ft., passive Perception 13"
"languages": ""
"cr": "0"
"traits":
- "desc": "The owl doesn't provoke opportunity attacks when it flies out of an enemy's\
    \ reach."
  "name": "Flyby"
- "desc": "The owl has advantage on Wisdom ([Perception](/3-Mechanics/CLI/rules/skills.md#Perception))\
    \ checks that rely on hearing or sight."
  "name": "Keen Hearing and Sight"
"actions":
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 1 slashing\
    \ damage."
  "name": "Talons"
"source":
- "MM"
- "RoT"
- "IMR"
- "IDRotF"
- "CM"
- "ToFW"
- "DoDk"
"image": "/3-Mechanics/CLI/bestiary/beast/token/owl.png"
```
^statblock

```encounter-table
name: Owl
creatures:
 - 1: Owl
```

## Environment

forest, arctic