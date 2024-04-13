---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/simic-hybrid
statblock: inline
aliases: ["Hybrid Flier"]
NoteIcon: monster
BestiaryType: humanoid (Simic hybrid)
SourceType: Bestiary
BookSource: Guildmasters' Guide to Ravnica p. 217
---
# [Hybrid Flier](3-Mechanics\CLI\bestiary\humanoid/hybrid-flier-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 217*  

## Simic Hybrids

The Guardian Project is a consequence of increasing tension within the Simic Combine as the threat of interguild conflict looms. Believing that the Simic must be prepared to fight for their lives when that conflict comes to a head, biomancers have created soldiers to help defend the guild. These hybrids (also called guardians, after the name of the project) are created from human, vedalken, and elf guild members who volunteer to be transformed.

```statblock
"name": "Hybrid Flier (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "Simic hybrid"
"alignment": "Neutral Good"
"ac": !!int "13"
"hp": !!int "39"
"hit_dice": "6d8 + 12"
"stats":
- !!int "12"
- !!int "16"
- !!int "14"
- !!int "11"
- !!int "10"
- !!int "11"
"speed": "30 ft., fly 40 ft."
"damage_resistances": "acid"
"senses": "passive Perception 10"
"languages": "Common plus any one language"
"cr": "2"
"actions":
- "desc": "The hybrid makes two javelin attacks. It can replace one javelin attack\
    \ with Spit Acid."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 30/120\
    \ ft., one target. Hit: 6 (1d6 + 3) piercing damage."
  "name": "Javelin"
- "desc": "Ranged Weapon Attack: +5 to hit, range 20/60 ft., one target. Hit:\
    \ 10 (4d4) acid damage."
  "name": "Spit Acid"
"source":
- "GGR"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/hybrid-flier.png"
```
^statblock

```encounter-table
name: Hybrid Flier
creatures:
 - 1: Hybrid Flier
```