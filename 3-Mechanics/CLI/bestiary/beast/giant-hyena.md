---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mm
- monster/cr/1
- monster/environment/desert
- monster/environment/forest
- monster/environment/grassland
- monster/environment/hill
- monster/size/large
- monster/type/beast
statblock: inline
aliases: ["Giant Hyena"]
NoteIcon: monster
BestiaryType: beast
SourceType: Bestiary
BookSource: Monster Manual p. 326. Available in the SRD and the Basic Rules.
---
# [Giant Hyena](3-Mechanics\CLI\bestiary\beast/giant-hyena.md)
*Source: Monster Manual p. 326. Available in the SRD and the Basic Rules.*  

```statblock
"name": "Giant Hyena"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "45"
"hit_dice": "6d10 + 12"
"stats":
- !!int "16"
- !!int "14"
- !!int "14"
- !!int "2"
- !!int "12"
- !!int "7"
"speed": "50 ft."
"skillsaves":
  "Perception": !!int "3"
"senses": "passive Perception 13"
"languages": ""
"cr": "1"
"traits":
- "desc": "When the hyena reduces a creature to 0 hit points with a melee attack on\
    \ its turn, the hyena can take a bonus action to move up to half its speed and\
    \ make a bite attack."
  "name": "Rampage"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 10 (2d6\
    \ + 3) piercing damage."
  "name": "Bite"
"source":
- "MM"
- "TftYP"
- "GoS"
- "BGDIA"
"image": "/3-Mechanics/CLI/bestiary/beast/token/giant-hyena.png"
```
^statblock

```encounter-table
name: Giant Hyena
creatures:
 - 1: Giant Hyena
```

## Environment

grassland, forest, hill, desert