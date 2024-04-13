---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/21
- monster/size/gargantuan
- monster/type/monstrosity
statblock: inline
aliases: ["Isperia"]
NoteIcon: monster
BestiaryType: monstrosity
SourceType: Bestiary
BookSource: Guildmasters' Guide to Ravnica p. 227
---
# [Isperia](3-Mechanics\CLI\bestiary\npc/isperia-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 227*  

Isperia is the current guildmaster of the Azorius Senate. As a sphinx, she is aloof and values solitude above all. However, she has been forced to give up her privacy to deal with the increased crime and chaos on Ravnica.

Isperia is devoted to her guild's belief that law is the ultimate bulwark against chaos, and it is her steady hand that guides the Azorius through these uncertain times. As guildmaster, Isperia serves as the supreme judge, a role that takes advantage of her encyclopedic knowledge of Ravnica's labyrinthine legal system.

If an encounter turns violent, Isperia refrains from using lethal force if possible, preferring to subdue a wrongdoing so that the legal system can mete out justice.

```statblock
"name": "Isperia (GGR)"
"size": "Gargantuan"
"type": "monstrosity"
"alignment": "Lawful Neutral"
"ac": !!int "17"
"hp": !!int "261"
"hit_dice": "18d20 + 72"
"stats":
- !!int "20"
- !!int "14"
- !!int "18"
- !!int "23"
- !!int "26"
- !!int "20"
"speed": "40 ft., fly 60 ft."
"saves":
  "Dexterity": !!int "9"
  "Wisdom": !!int "15"
  "Intelligence": !!int "13"
  "Constitution": !!int "11"
"skillsaves":
  "Insight": !!int "15"
  "Perception": !!int "15"
  "History": !!int "13"
  "Arcana": !!int "13"
"damage_immunities": "psychic; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "[charmed](/3-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [frightened](/3-Mechanics/CLI/rules/conditions.md#frightened)"
"senses": "truesight 120 ft., passive Perception 25"
"languages": "Common, Sphinx"
"cr": "21"
"traits":
- "desc": "Isperia's innate spellcasting ability is Wisdom (spell save DC 23). Isperia\
    \ can innately cast [imprisonment](/3-Mechanics/CLI/spells/imprisonment.md) twice\
    \ per day, requiring no material components.\n\n2/day: [imprisonment](/3-Mechanics/CLI/spells/imprisonment.md)"
  "name": "innate"
- "desc": "Isperia is a 15th-level Azorius spellcaster. Her spellcasting ability is\
    \ Wisdom (spell save DC 23, +14 to hit with spell attacks). Isperia has the following\
    \ cleric spells prepared:\n\nCantrips (at will): [guidance](/3-Mechanics/CLI/spells/guidance.md),\
    \ [light](/3-Mechanics/CLI/spells/light.md), [resistance](/3-Mechanics/CLI/spells/resistance.md),\
    \ [sacred flame](/3-Mechanics/CLI/spells/sacred-flame.md), [thaumaturgy](/3-Mechanics/CLI/spells/thaumaturgy.md)\n\
    \n1st level (4 slots): [command](/3-Mechanics/CLI/spells/command.md), [detect\
    \ evil and good](/3-Mechanics/CLI/spells/detect-evil-and-good.md), [ensnaring\
    \ strike](/3-Mechanics/CLI/spells/ensnaring-strike.md), [sanctuary](/3-Mechanics/CLI/spells/sanctuary.md),\
    \ [shield of faith](/3-Mechanics/CLI/spells/shield-of-faith.md)\n\n2nd level\
    \ (3 slots): [arcane lock](/3-Mechanics/CLI/spells/arcane-lock.md), [augury](/3-Mechanics/CLI/spells/augury.md),\
    \ [calm emotions](/3-Mechanics/CLI/spells/calm-emotions.md), [hold person](/3-Mechanics/CLI/spells/hold-person.md),\
    \ [silence](/3-Mechanics/CLI/spells/silence.md), [zone of truth](/3-Mechanics/CLI/spells/zone-of-truth.md)\n\
    \n3rd level (3 slots): [bestow curse](/3-Mechanics/CLI/spells/bestow-curse.md),\
    \ [clairvoyance](/3-Mechanics/CLI/spells/clairvoyance.md), [counterspell](/3-Mechanics/CLI/spells/counterspell.md),\
    \ [dispel magic](/3-Mechanics/CLI/spells/dispel-magic.md), [tongues](/3-Mechanics/CLI/spells/tongues.md)\n\
    \n4th level (3 slots): [divination](/3-Mechanics/CLI/spells/divination.md),\
    \ [locate creature](/3-Mechanics/CLI/spells/locate-creature.md)\n\n5th level\
    \ (2 slots): [dispel evil and good](/3-Mechanics/CLI/spells/dispel-evil-and-good.md),\
    \ [scrying](/3-Mechanics/CLI/spells/scrying.md)\n\n6th level (1 slots): [word\
    \ of recall](/3-Mechanics/CLI/spells/word-of-recall.md)\n\n7th level (1 slots):\
    \ [divine word](/3-Mechanics/CLI/spells/divine-word.md)\n\n8th level (1 slots):\
    \ [antimagic field](/3-Mechanics/CLI/spells/antimagic-field.md)"
  "name": "spells"
- "desc": "Isperia is immune to any effect that would sense her emotions or read her\
    \ thoughts, as well as any divination spell that she refuses. Wisdom (Insight)\
    \ checks made to ascertain her intentions or sincerity have disadvantage."
  "name": "Inscrutable"
- "desc": "If Isperia fails a saving throw, she can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "Isperia has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "Isperia makes two claw attacks. She can cast a spell with a casting time\
    \ of 1 action in place of one claw attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +12 to hit, reach 5 ft., one target. Hit: 21 (3d10\
    \ + 5) slashing damage. If the target is a creature, it must succeed on a DC\
    \ 23 Wisdom saving throw or take 14 (4d6) psychic damage after each attack it\
    \ makes against Isperia before the start of her next turn."
  "name": "Claw"
- "desc": "Isperia chooses up to three creatures she can see within 90 feet of her.\
    \ Each target must succeed on a DC 23 Intelligence saving throw or Isperia chooses\
    \ an action for that target: Attack, Cast a Spell, Dash, Disengage, Dodge, Help,\
    \ Hide, Ready, Search, or Use an Object. The affected target can't take that action\
    \ for 1 minute. At the end of each of the target's turns, it can end the effect\
    \ on itself with a successful DC 23 Intelligence saving throw. A target that succeeds\
    \ on the saving throw becomes immune to Isperia's Supreme Legal Authority for\
    \ 24 hours."
  "name": "Supreme Legal Authority"
"legendary_actions":
- "desc": "Isperia makes one claw attack."
  "name": "Claw Attack"
- "desc": "Isperia casts a spell of 3rd level or lower from her list of prepared spells,\
    \ using a spell slot as normal."
  "name": "Cast a Spell (Costs 2 Actions)"
- "desc": "Isperia uses Supreme Legal Authority."
  "name": "Supreme Legal Authority (Costs 3 Actions)"
"source":
- "GGR"
"image": "/3-Mechanics/CLI/bestiary/npc/token/isperia.png"
```
^statblock

```encounter-table
name: Isperia
creatures:
 - 1: Isperia
```