---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/2
- monster/size/medium
- monster/type/humanoid/any-race
statblock: inline
aliases: ["Rakdos Lampooner"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Guildmasters' Guide to Ravnica p. 248
---
# [Rakdos Lampooner](3-Mechanics\CLI\bestiary\humanoid/rakdos-lampooner-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 248*  

One of the most effective weapons in the Rakdos cult's arsenal is satire, and a Rakdos lampooner is a virtuoso of that art. Lampooners generally reserve their mockery for people and guilds that have seized an outsized measure of power, those who need to be taken down a peg, rather than piling further humiliation onto those who are already struggling. They use masks, marionettes, or effigies to caricature public figures, or sometimes play pranks on those individuals directly in the streets.

```statblock
"name": "Rakdos Lampooner (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Chaotic Evil"
"ac": !!int "12"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"stats":
- !!int "11"
- !!int "12"
- !!int "13"
- !!int "12"
- !!int "9"
- !!int "18"
"speed": "30 ft."
"skillsaves":
  "Deception": !!int "6"
  "Performance": !!int "6"
"senses": "passive Perception 9"
"languages": "Common plus any one language"
"cr": "2"
"traits":
- "desc": "The lampooner is a 4th-level Rakdos spellcaster. Its spellcasting ability\
    \ is Charisma (spell save DC 14, +6 to hit with spell attacks). It knows the following\
    \ bard spells:\n\nCantrips (at will): [dancing lights](/3-Mechanics/CLI/spells/dancing-lights.md),\
    \ [minor illusion](/3-Mechanics/CLI/spells/minor-illusion.md), [vicious mockery](/3-Mechanics/CLI/spells/vicious-mockery.md)\n\
    \n1st level (4 slots): [bane](/3-Mechanics/CLI/spells/bane.md), [dissonant\
    \ whispers](/3-Mechanics/CLI/spells/dissonant-whispers.md), [silent image](/3-Mechanics/CLI/spells/silent-image.md),\
    \ [Tasha's hideous laughter](/3-Mechanics/CLI/spells/tashas-hideous-laughter.md),\
    \ [thunderwave](/3-Mechanics/CLI/spells/thunderwave.md)\n\n2nd level (3 slots):\
    \ [crown of madness](/3-Mechanics/CLI/spells/crown-of-madness.md), [enthrall](/3-Mechanics/CLI/spells/enthrall.md),\
    \ [suggestion](/3-Mechanics/CLI/spells/suggestion.md)"
  "name": "spells"
"actions":
- "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 2 (1d4)\
    \ bludgeoning damage."
  "name": "Club"
"source":
- "GGR"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/rakdos-lampooner.png"
```
^statblock

```encounter-table
name: Rakdos Lampooner
creatures:
 - 1: Rakdos Lampooner
```