---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/6
- monster/size/large
- monster/type/giant
statblock: inline
aliases: ["Orzhov Giant"]
NoteIcon: monster
BestiaryType: giant
SourceType: Bestiary
BookSource: Guildmasters' Guide to Ravnica p. 202
---
# [Orzhov Giant](3-Mechanics\CLI\bestiary\giant/orzhov-giant-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 202*  

A few giants join the ranks of the Orzhov Syndicate and serve as guards, executioners, and thugs-the muscle of the guild. The presence of Orzhov giants in markets and streets serves as an effective reminder for business owners to keep their payments up to date.

## Giants

Giants use their tremendous size and strength to advance the cause of no less than four guilds. In the Boros Legion and the Orzhov Syndicate, they are cunning soldiers. The giants of the Cult of Rakdos and the Gruul Clans are no less effective but lack discipline.

```statblock
"name": "Orzhov Giant (GGR)"
"size": "Large"
"type": "giant"
"alignment": "Lawful Evil"
"ac": !!int "18"
"hp": !!int "84"
"hit_dice": "8d10 + 40"
"stats":
- !!int "23"
- !!int "13"
- !!int "21"
- !!int "12"
- !!int "13"
- !!int "8"
"speed": "40 ft."
"saves":
  "Dexterity": !!int "4"
  "Wisdom": !!int "4"
  "Constitution": !!int "8"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common, Giant"
"cr": "6"
"traits":
- "desc": "As a bonus action, the giant can target a creature it can see within 30\
    \ feet of it and make that creature its focus. The target remains the giant's\
    \ focus for 1 minute, or until either the target or the giant drops to 0 hit points.\
    \ When the giant makes an attack roll against its focus, it adds a d4 to its\
    \ attack roll. If the giant attacks a different target while it has a focus, it\
    \ subtracts a d4 from its attack roll."
  "name": "Focus"
"actions":
- "desc": "The giant makes two greataxe attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +9 to hit, reach 10 ft., one target. Hit: 25 (3d12\
    \ + 6) slashing damage. If the Orzhov giant scores a critical hit, it rolls the\
    \ damage dice three times, instead of twice."
  "name": "Greataxe"
- "desc": "Ranged Weapon Attack: +9 to hit, range 60/240 ft., one target. Hit:\
    \ 28 (4d10 + 6) bludgeoning damage."
  "name": "Rock"
"source":
- "GGR"
"image": "/3-Mechanics/CLI/bestiary/giant/token/orzhov-giant.png"
```
^statblock

```encounter-table
name: Orzhov Giant
creatures:
 - 1: Orzhov Giant
```