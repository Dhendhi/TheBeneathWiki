---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/simic-hybrid
statblock: inline
aliases: ["Hybrid Brute"]
NoteIcon: monster
BestiaryType: humanoid (Simic hybrid)
SourceType: Bestiary
BookSource: Guildmasters' Guide to Ravnica p. 217
---
# [Hybrid Brute](3-Mechanics\CLI\bestiary\humanoid/hybrid-brute-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 217*  

## Simic Hybrids

The Guardian Project is a consequence of increasing tension within the Simic Combine as the threat of interguild conflict looms. Believing that the Simic must be prepared to fight for their lives when that conflict comes to a head, biomancers have created soldiers to help defend the guild. These hybrids (also called guardians, after the name of the project) are created from human, vedalken, and elf guild members who volunteer to be transformed.

```statblock
"name": "Hybrid Brute (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "Simic hybrid"
"alignment": "Neutral Good"
"ac": !!int "18"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"stats":
- !!int "18"
- !!int "11"
- !!int "15"
- !!int "8"
- !!int "11"
- !!int "9"
"speed": "30 ft."
"senses": "passive Perception 10"
"languages": "Common plus any one language"
"cr": "2"
"traits":
- "desc": "The hybrid can breathe air and water."
  "name": "Amphibious"
"actions":
- "desc": "The hybrid makes two claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 7 (1d6\
    \ + 4) slashing damage."
  "name": "Claw"
"source":
- "GGR"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/hybrid-brute.png"
```
^statblock

```encounter-table
name: Hybrid Brute
creatures:
 - 1: Hybrid Brute
```