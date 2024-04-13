---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/6
- monster/size/medium
- monster/type/humanoid/any-race
statblock: inline
aliases: ["Lawmage"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Guildmasters' Guide to Ravnica p. 228
---
# [Lawmage](3-Mechanics\CLI\bestiary\humanoid/lawmage-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 228*  

The Azorius Senate has spellcasters who are trained to capture lawbreakers and bring them to justice. A lawmage's magic is focused on restraining criminals and on protecting bystanders from becoming casualties when arresters are pursuing malefactors. A significant proportion of the guild's vedalken are lawmages.

```statblock
"name": "Lawmage (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Lawful Neutral"
"ac": !!int "15"
"hp": !!int "84"
"hit_dice": "13d8 + 26"
"stats":
- !!int "13"
- !!int "12"
- !!int "14"
- !!int "17"
- !!int "14"
- !!int "13"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "5"
  "Intelligence": !!int "6"
"skillsaves":
  "Perception": !!int "5"
  "Arcana": !!int "6"
  "Persuasion": !!int "4"
"senses": "passive Perception 15"
"languages": "Common plus any one language"
"cr": "6"
"traits":
- "desc": "The lawmage is an 8th-level Azorius spellcaster. Its spellcasting ability\
    \ is Intelligence (spell save DC 14, +6 to hit with spell attacks). The lawmage\
    \ has the following wizard spells prepared:\n\nCantrips (at will): [fire bolt](/3-Mechanics/CLI/spells/fire-bolt.md),\
    \ [friends](/3-Mechanics/CLI/spells/friends.md), [light](/3-Mechanics/CLI/spells/light.md),\
    \ [message](/3-Mechanics/CLI/spells/message.md)\n\n1st level (4 slots): [alarm](/3-Mechanics/CLI/spells/alarm.md),\
    \ [expeditious retreat](/3-Mechanics/CLI/spells/expeditious-retreat.md), [shield](/3-Mechanics/CLI/spells/shield.md)\n\
    \n2nd level (3 slots): [arcane lock](/3-Mechanics/CLI/spells/arcane-lock.md),\
    \ [detect thoughts](/3-Mechanics/CLI/spells/detect-thoughts.md), [hold person](/3-Mechanics/CLI/spells/hold-person.md)\n\
    \n3rd level (3 slots): [clairvoyance](/3-Mechanics/CLI/spells/clairvoyance.md),\
    \ [dispel magic](/3-Mechanics/CLI/spells/dispel-magic.md), [slow](/3-Mechanics/CLI/spells/slow.md)\n\
    \n4th level (2 slots): [locate creature](/3-Mechanics/CLI/spells/locate-creature.md),\
    \ [stoneskin](/3-Mechanics/CLI/spells/stoneskin.md)"
  "name": "spells"
"actions":
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d6\
    \ + 1) bludgeoning damage, or 5 (1d8 + 1) bludgeoning damage if used with two\
    \ hands."
  "name": "Quarterstaff"
"source":
- "GGR"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/lawmage.png"
```
^statblock

```encounter-table
name: Lawmage
creatures:
 - 1: Lawmage
```