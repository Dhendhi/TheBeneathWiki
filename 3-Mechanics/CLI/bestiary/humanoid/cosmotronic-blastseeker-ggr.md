---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/4
- monster/size/medium
- monster/type/humanoid/any-race
statblock: inline
aliases: ["Cosmotronic Blastseeker"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Guildmasters' Guide to Ravnica p. 242
---
# [Cosmotronic Blastseeker](3-Mechanics\CLI\bestiary\humanoid/cosmotronic-blastseeker-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 242*  

While chemisters focus on inventing new tools, weapons, and other devices for the guild to use, the role of a blastseeker is to put those devices to work. Despite the name, not all such devices produce explosions, but all the most interesting ones (from the Izzet perspective) do.

```statblock
"name": "Cosmotronic Blastseeker (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Chaotic Neutral"
"ac": !!int "15"
"hp": !!int "37"
"hit_dice": "5d8 + 15"
"stats":
- !!int "14"
- !!int "15"
- !!int "16"
- !!int "18"
- !!int "9"
- !!int "12"
"speed": "30 ft."
"saves":
  "Dexterity": !!int "4"
  "Constitution": !!int "5"
"skillsaves":
  "Intimidation": !!int "3"
  "Perception": !!int "1"
  "Arcana": !!int "6"
"senses": "passive Perception 11"
"languages": "any one language (usually Common)"
"cr": "4"
"traits":
- "desc": "The blastseeker's innate spellcasting ability is Intelligence (spell save\
    \ DC 14, +6 to hit with spell attacks). The blastseeker can innately cast the\
    \ following spells, requiring no components other than its Izzet gear, which doesn't\
    \ function for others:\n\n2/day: [fireball](/3-Mechanics/CLI/spells/fireball.md)\n\
    \n3/day each: [scorching ray](/3-Mechanics/CLI/spells/scorching-ray.md), [shield](/3-Mechanics/CLI/spells/shield.md),\
    \ [thunderwave](/3-Mechanics/CLI/spells/thunderwave.md)"
  "name": "innate"
- "desc": "When the blastseeker rolls damage for a spell, it can reroll up to four\
    \ dice of damage. It must use the new dice."
  "name": "Empowered Spell (3/Day)"
- "desc": "The blastseeker makes one attack roll, ability check, or saving throw with\
    \ advantage."
  "name": "Tides of Chaos (1/Day)"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8\
    \ + 2) bludgeoning damage, or 7 (1d10 + 2) bludgeoning damage if used with\
    \ two hands."
  "name": "Warhammer"
"source":
- "GGR"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/cosmotronic-blastseeker.png"
```
^statblock

```encounter-table
name: Cosmotronic Blastseeker
creatures:
 - 1: Cosmotronic Blastseeker
```