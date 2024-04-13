---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/1
- monster/size/medium
- monster/type/humanoid/any-race
statblock: inline
aliases: ["Thought Spy"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Guildmasters' Guide to Ravnica p. 233
---
# [Thought Spy](3-Mechanics\CLI\bestiary\humanoid/thought-spy-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 233*  

Thought spies form the backbone of House Dimir's covert operations. They are trained in stealth and infiltration, tactics that they supplement with rigorously developed mental abilities. To ensure that no secrets slip through Dimir's fingers, they infiltrate rival guilds. In addition to traditional means of gathering intelligence, thought spies use their magic to spy on the thoughts of their targets.

```statblock
"name": "Thought Spy (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Neutral Evil"
"ac": !!int "13"
"hp": !!int "27"
"hit_dice": "6d8"
"stats":
- !!int "11"
- !!int "14"
- !!int "10"
- !!int "16"
- !!int "13"
- !!int "14"
"speed": "30 ft."
"skillsaves":
  "Sleight of Hand": !!int "4"
  "Deception": !!int "6"
  "Stealth": !!int "4"
  "Investigation": !!int "5"
  "Insight": !!int "3"
  "Perception": !!int "3"
"senses": "darkvision 30 ft., passive Perception 13"
"languages": "Common plus any one language"
"cr": "1"
"traits":
- "desc": "The thought spy's innate spellcasting ability is Intelligence (spell save\
    \ DC 13). The thought spy can innately cast the following spells, requiring no\
    \ components:\n\nAt will: [charm person](/3-Mechanics/CLI/spells/charm-person.md),\
    \ [disguise self](/3-Mechanics/CLI/spells/disguise-self.md), [encode thoughts](/3-Mechanics/CLI/spells/encode-thoughts-ggr.md)\
    \ (see chapter 2)\n\n1/day each: [blur](/3-Mechanics/CLI/spells/blur.md),\
    \ [detect thoughts](/3-Mechanics/CLI/spells/detect-thoughts.md), [gaseous form](/3-Mechanics/CLI/spells/gaseous-form.md)"
  "name": "innate"
- "desc": "On each of its turns, the thought spy can use a bonus action to take the\
    \ Dash, Disengage, or Hide action."
  "name": "Cunning Action"
"actions":
- "desc": "The thought spy makes two melee attacks, or it makes three ranged attacks\
    \ with its daggers."
  "name": "Multiattack"
- "desc": "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 4 (1d4 + 2) piercing damage."
  "name": "Dagger"
- "desc": "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 6 (1d8\
    \ + 2) piercing damage."
  "name": "Rapier"
"source":
- "GGR"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/thought-spy.png"
```
^statblock

```encounter-table
name: Thought Spy
creatures:
 - 1: Thought Spy
```