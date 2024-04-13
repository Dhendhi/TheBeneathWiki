---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/10
- monster/size/medium
- monster/type/humanoid/any-race
statblock: inline
aliases: ["Biomancer"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Guildmasters' Guide to Ravnica p. 256
---
# [Biomancer](3-Mechanics\CLI\bestiary\humanoid/biomancer-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 256*  

Nearly all the innovation and advancement in Simic bioengineering comes from the work of biomancers. Specialists in hybridizing and altering creatures through a mixture of science and magic, they have spawned countless hybrids and krasis in search of the perfect union between nature and civilization.

```statblock
"name": "Biomancer (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Neutral Good"
"ac": !!int "17"
"hp": !!int "110"
"hit_dice": "17d8 + 34"
"stats":
- !!int "10"
- !!int "15"
- !!int "14"
- !!int "20"
- !!int "14"
- !!int "15"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "6"
  "Intelligence": !!int "9"
"skillsaves":
  "Nature": !!int "9"
  "Arcana": !!int "9"
"senses": "passive Perception 12"
"languages": "Common plus any one language"
"cr": "10"
"traits":
- "desc": "The biomancer is a 16th-level Simic spellcaster. Its spellcasting ability\
    \ is Intelligence (spell save DC 17, +9 to hit with spell attacks). The biomancer\
    \ has the following wizard spells prepared:\n\nCantrips (at will): [acid splash](/3-Mechanics/CLI/spells/acid-splash.md),\
    \ [light](/3-Mechanics/CLI/spells/light.md), [mending](/3-Mechanics/CLI/spells/mending.md),\
    \ [poison spray](/3-Mechanics/CLI/spells/poison-spray.md), [shocking grasp](/3-Mechanics/CLI/spells/shocking-grasp.md)\n\
    \n1st level (4 slots): [detect magic](/3-Mechanics/CLI/spells/detect-magic.md),\
    \ [grease](/3-Mechanics/CLI/spells/grease.md), [shield](/3-Mechanics/CLI/spells/shield.md)\n\
    \n2nd level (3 slots): [alter self](/3-Mechanics/CLI/spells/alter-self.md),\
    \ [darkvision](/3-Mechanics/CLI/spells/darkvision.md), [enlarge/reduce](/3-Mechanics/CLI/spells/enlarge-reduce.md),\
    \ [hold person](/3-Mechanics/CLI/spells/hold-person.md)\n\n3rd level (3 slots):\
    \ [counterspell](/3-Mechanics/CLI/spells/counterspell.md), [dispel magic](/3-Mechanics/CLI/spells/dispel-magic.md),\
    \ [haste](/3-Mechanics/CLI/spells/haste.md), [protection from energy](/3-Mechanics/CLI/spells/protection-from-energy.md)\n\
    \n4th level (3 slots): [confusion](/3-Mechanics/CLI/spells/confusion.md),\
    \ [conjure minor elementals](/3-Mechanics/CLI/spells/conjure-minor-elementals.md),\
    \ [polymorph](/3-Mechanics/CLI/spells/polymorph.md)\n\n5th level (2 slots):\
    \ [cone of cold](/3-Mechanics/CLI/spells/cone-of-cold.md), [creation](/3-Mechanics/CLI/spells/creation.md),\
    \ [hold monster](/3-Mechanics/CLI/spells/hold-monster.md)\n\n6th level (1 slots):\
    \ [move earth](/3-Mechanics/CLI/spells/move-earth.md), [wall of ice](/3-Mechanics/CLI/spells/wall-of-ice.md)\n\
    \n7th level (1 slots): [prismatic spray](/3-Mechanics/CLI/spells/prismatic-spray.md)\n\
    \n8th level (1 slots): [control weather](/3-Mechanics/CLI/spells/control-weather.md)"
  "name": "spells"
- "desc": "The biomancer magically emanates life-giving energy within 30 feet of itself.\
    \ Any ally of the biomancer that starts its turn there regains 5 (1d10) hit\
    \ points."
  "name": "Bolstering Presence"
- "desc": "The biomancer has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) slashing damage."
  "name": "Scimitar"
"source":
- "GGR"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/biomancer.png"
```
^statblock

```encounter-table
name: Biomancer
creatures:
 - 1: Biomancer
```