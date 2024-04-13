---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/11
- monster/size/large
- monster/type/monstrosity
statblock: inline
aliases: ["Sphinx of Judgment"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Guildmasters' Guide to Ravnica p. 183
---
# [Sphinx of Judgment](3-Mechanics\CLI\bestiary\monstrosity/sphinx-of-judgment-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 183*  

```statblock
"name": "Sphinx of Judgment (GGR)"
"size": "Large"
"type": "monstrosity"
"alignment": "Lawful Neutral"
"ac": !!int "17"
"hp": !!int "136"
"hit_dice": "16d10 + 48"
"stats":
- !!int "18"
- !!int "15"
- !!int "16"
- !!int "18"
- !!int "18"
- !!int "18"
"speed": "40 ft., fly 60 ft."
"skillsaves":
  "Religion": !!int "8"
  "Perception": !!int "8"
  "History": !!int "12"
  "Arcana": !!int "12"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "psychic"
"condition_immunities": "[charmed](/3-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [frightened](/3-Mechanics/CLI/rules/conditions.md#frightened)"
"senses": "truesight 120 ft., passive Perception 18"
"languages": "Common, Sphinx"
"cr": "11"
"traits":
- "desc": "The sphinx is a 9th-level spellcaster. Its spellcasting ability is Intelligence\
    \ (spell save DC 16, +8 to hit with spell attacks). It requires no material components\
    \ to cast its spells. The sphinx has the following wizard spells prepared:\n\n\
    Cantrips (at will): [friends](/3-Mechanics/CLI/spells/friends.md), [mage hand](/3-Mechanics/CLI/spells/mage-hand.md),\
    \ [message](/3-Mechanics/CLI/spells/message.md)\n\n1st level (4 slots): [command](/3-Mechanics/CLI/spells/command.md),\
    \ [ensnaring strike](/3-Mechanics/CLI/spells/ensnaring-strike.md), [shield](/3-Mechanics/CLI/spells/shield.md)\n\
    \n2nd level (3 slots): [calm emotions](/3-Mechanics/CLI/spells/calm-emotions.md),\
    \ [hold person](/3-Mechanics/CLI/spells/hold-person.md), [suggestion](/3-Mechanics/CLI/spells/suggestion.md)\n\
    \n3rd level (3 slots): [clairvoyance](/3-Mechanics/CLI/spells/clairvoyance.md),\
    \ [counterspell](/3-Mechanics/CLI/spells/counterspell.md), [dispel magic](/3-Mechanics/CLI/spells/dispel-magic.md)\n\
    \n4th level (3 slots): [banishment](/3-Mechanics/CLI/spells/banishment.md),\
    \ [divination](/3-Mechanics/CLI/spells/divination.md)\n\n5th level (1 slots):\
    \ [dominate person](/3-Mechanics/CLI/spells/dominate-person.md)"
  "name": "spells"
- "desc": "The sphinx is immune to any effect that would sense its emotions or read\
    \ its thoughts, as well as any divination spell that it refuses. Wisdom (Insight)\
    \ checks made to ascertain the sphinx's intentions or sincerity have disadvantage."
  "name": "Inscrutable"
- "desc": "The sphinx's weapon attacks are magical."
  "name": "Magic Weapons"
"actions":
- "desc": "The sphinx makes two claw attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one target. Hit: 13 (2d8\
    \ + 4) slashing damage."
  "name": "Claw"
"legendary_actions":
- "desc": "The sphinx makes one claw attack."
  "name": "Claw Attack"
- "desc": "The sphinx magically teleports, along with any equipment it is wearing\
    \ or carrying, up to 120 feet to an unoccupied space it can see."
  "name": "Teleport (Costs 2 Actions)"
- "desc": "The sphinx casts a spell from its list of prepared spells, using a spell\
    \ slot as normal."
  "name": "Cast a Spell (Costs 3 Actions)"
"source":
- "GGR"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/sphinx-of-judgment.png"
```
^statblock

```encounter-table
name: Sphinx of Judgment
creatures:
 - 1: Sphinx of Judgment
```