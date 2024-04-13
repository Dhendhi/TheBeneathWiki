---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/4
- monster/size/medium
- monster/type/humanoid/any-race
statblock: inline
aliases: ["Reckoner"]
NoteIcon: monster
BestiaryType: humanoid (any race)
SourceType: Bestiary
BookSource: Guildmasters' Guide to Ravnica p. 231
---
# [Reckoner](3-Mechanics\CLI\bestiary\humanoid/reckoner-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 231*  

Boros reckoners combine physical power and magical prowess, serving as the shock troops of the legion. They are adept at breaking up mobs and organized lines of defense. Sometimes described as living thunderstorms, reckoners charge their bodies with lightning that bursts forth in their spells and lashes out at enemies who harm them. Many reckoners are minotaurs.

```statblock
"name": "Reckoner (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Lawful Neutral"
"ac": !!int "18"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"stats":
- !!int "16"
- !!int "12"
- !!int "15"
- !!int "15"
- !!int "12"
- !!int "10"
"speed": "30 ft."
"skillsaves":
  "Intimidation": !!int "2"
  "Perception": !!int "3"
  "Arcana": !!int "4"
"senses": "passive Perception 13"
"languages": "Common plus any one language"
"cr": "4"
"traits":
- "desc": "The reckoner is a 5th-level Boros spellcaster. Its spellcasting ability\
    \ is Intelligence (spell save DC 12, +4 to hit with spell attacks). The reckoner\
    \ has the following wizard spells prepared:\n\nCantrips (at will): [blade\
    \ ward](/3-Mechanics/CLI/spells/blade-ward.md), [light](/3-Mechanics/CLI/spells/light.md),\
    \ [message](/3-Mechanics/CLI/spells/message.md), [shocking grasp](/3-Mechanics/CLI/spells/shocking-grasp.md)\n\
    \n1st level (4 slots): [guiding bolt](/3-Mechanics/CLI/spells/guiding-bolt.md),\
    \ [shield](/3-Mechanics/CLI/spells/shield.md), [thunderwave](/3-Mechanics/CLI/spells/thunderwave.md),\
    \ [witch bolt](/3-Mechanics/CLI/spells/witch-bolt.md)\n\n2nd level (3 slots):\
    \ [blur](/3-Mechanics/CLI/spells/blur.md), [levitate](/3-Mechanics/CLI/spells/levitate.md)\n\
    \n3rd level (2 slots): [lightning bolt](/3-Mechanics/CLI/spells/lightning-bolt.md)"
  "name": "spells"
- "desc": "The reckoner has advantage on initiative rolls."
  "name": "First Strike"
"actions":
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) slashing damage, or 8 (1d10 + 3) slashing damage if used with two hands."
  "name": "Longsword"
"reactions":
- "desc": "When a creature hits the reckoner with an attack, the attacker takes lightning\
    \ damage equal to half the damage dealt by the attack."
  "name": "Lightning Backlash (Recharge 5-6)"
"source":
- "GGR"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/reckoner.png"
```
^statblock

```encounter-table
name: Reckoner
creatures:
 - 1: Reckoner
```