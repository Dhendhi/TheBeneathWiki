---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/8
- monster/size/medium
- monster/type/undead
statblock: inline
aliases: ["Obzedat Ghost"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Guildmasters' Guide to Ravnica p. 245
---
# [Obzedat Ghost](3-Mechanics\CLI\bestiary\undead/obzedat-ghost-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 245*  

The ghosts who make up the Obzedat are traditionally called patriarchs, though they can be male or female. They are the oldest, wealthiest, and most influential oligarchs of the Orzhov Syndicate. They have been dead for centuries, but they refuse to let go of the fortunes they amassed in life. Addicted to power and prestige, these patriarchs continue to dominate the guild and accumulate even larger fortunes.

## Mostly Unanimous

The ghosts of the Obzedat function as a unit, driven by their shared desire to accumulate ever more wealth for the guild. In times of disagreement, the eldest of the council exerts his seniority to bend the council to his will.

## Grandfather Karlov

The head of the council, who gives final approval to its decisions and breaks ties within the group, is Karlov, known as Grandfather. In life, Karlov was the greediest of Orzhov oligarchs, and his many centuries as a spirit have not diminished his hunger for more wealth.

## Undead Nature

An Obzedat ghost doesn't require air, food, drink, or sleep.

The Ghost Council's Traits

Ideal: "Influence is measured in power, status, and money, but mostly money."

Bond: "Gather as much as you can while you can, for when you die, you will take it with you."

Flaw: "Everyone has a price."

```statblock
"name": "Obzedat Ghost (GGR)"
"size": "Medium"
"type": "undead"
"alignment": "Lawful Evil"
"ac": !!int "14"
"hp": !!int "110"
"hit_dice": "20d8 + 20"
"stats":
- !!int "10"
- !!int "10"
- !!int "13"
- !!int "18"
- !!int "20"
- !!int "17"
"speed": "0 ft., fly 30 ft. (hover)"
"saves":
  "Wisdom": !!int "8"
  "Intelligence": !!int "7"
"skillsaves":
  "Insight": !!int "8"
  "Perception": !!int "8"
"damage_resistances": "acid; cold; fire; lightning; thunder; bludgeoning, piercing,\
  \ slashing from nonmagical attacks"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/3-Mechanics/CLI/rules/conditions.md#exhaustion), [grappled](/3-Mechanics/CLI/rules/conditions.md#grappled),\
  \ [paralyzed](/3-Mechanics/CLI/rules/conditions.md#paralyzed), [petrified](/3-Mechanics/CLI/rules/conditions.md#petrified),\
  \ [poisoned](/3-Mechanics/CLI/rules/conditions.md#poisoned), [prone](/3-Mechanics/CLI/rules/conditions.md#prone),\
  \ [restrained](/3-Mechanics/CLI/rules/conditions.md#restrained)"
"senses": "darkvision 60 ft., passive Perception 18"
"languages": "Common"
"cr": "8"
"traits":
- "desc": "The ghost's innate spellcasting ability is Wisdom (spell save DC 16, +8\
    \ to hit with spell attacks). It can innately cast the following spells, requiring\
    \ no components:\n\nAt will: [chill touch](/3-Mechanics/CLI/spells/chill-touch.md)\
    \ (at 5th level, and the ghost regains hit points equal to half the amount of\
    \ damage the target takes)\n\n1/day each: [sanctuary](/3-Mechanics/CLI/spells/sanctuary.md),\
    \ [spirit guardians](/3-Mechanics/CLI/spells/spirit-guardians.md) (at 4th level)"
  "name": "innate"
- "desc": "The ghost has a trait based on who it is, as shown below:\n\n- Enezesku\
    \ Enfeebling Ray. Enezesku's Innate Spellcasting trait includes [ray of enfeeblement](/3-Mechanics/CLI/spells/ray-of-enfeeblement.md),\
    \ which he can cast at will.  \n- Fautomni Undead Fortitude. If damage reduces\
    \ Fautomni to 0 hit points, he must make a Constitution saving throw with a DC\
    \ of 5 + the damage taken, unless the damage is radiant or from a critical hit.\
    \ On a success, Fautomni drops to 1 hit point instead.  \n- Karlov Unnatural\
    \ Vigor. When Karlov regains hit points, he has advantage on attack rolls he\
    \ makes on his next turn.  \n- Vuliev Teleportation. Vuliev's Innate Spellcasting\
    \ trait includes [misty step](/3-Mechanics/CLI/spells/misty-step.md), which he\
    \ can cast at will.  \n- Xil Xaxosz Lingering Spite. When Xil Xaxosz is reduced\
    \ to 0 hit points, his incorporeal form explodes in a burst of necrotic energy.\
    \ Each creature within 5 feet of him must make a DC 16 Constitution saving throw,\
    \ taking 14 (4d6) necrotic damage on a failed save, or half as much damage on\
    \ a successful one.  "
  "name": "Council of Five"
- "desc": "The ghost can see 60 feet into the Ethereal Plane when it is on the Material\
    \ Plane, and vice versa."
  "name": "Ethereal Sight"
- "desc": "The ghost can move through other creatures and objects as if they were\
    \ difficult terrain. It takes 5 (1d10) force damage if it ends its turn inside\
    \ an object."
  "name": "Incorporeal Movement"
- "desc": "If the ghost fails a saving throw, it can choose to succeed instead."
  "name": "Legendary Resistance (1/Day)"
"actions":
- "desc": "Melee Weapon Attack: +8 to hit, reach 5 ft., one creature. Hit: 18\
    \ (4d8) necrotic damage, and the ghost regains hit points equal to half the\
    \ amount of damage the target takes. The target must succeed on a DC 13 Constitution\
    \ saving throw or its hit point maximum is reduced by an amount equal to the damage\
    \ taken. The target dies if its hit point maximum is reduced to 0. This reduction\
    \ to the target's hit point maximum lasts until the target finishes a long rest."
  "name": "Life Drain"
- "desc": "The ghost summons the other four members of the Obzedat. At the start of\
    \ the ghost's next turn, the other members appear in unoccupied spaces within\
    \ 30 feet of the summoner. The ghosts each roll initiative when they appear."
  "name": "Convene the Ghost Council"
"legendary_actions":
- "desc": "If five Obzedat ghosts are all within 30 feet of each other, they can collectively\
    \ take 3 legendary actions, choosing from the options below. Only one legendary\
    \ action option can be used at a time, and only at the end of another creature's\
    \ turn. Obzedat ghosts regain spent legendary actions at the start of the turn\
    \ of the ghost with the highest initiative."
  "name": ""
- "desc": "A target that all of the Obzedat ghosts can see must succeed on a DC 16\
    \ Wisdom saving throw or bow until the end of its next turn. Until this bow ends,\
    \ the target can't take actions or reactions, and its speed is 0 and can't be\
    \ increased."
  "name": "Forced Obedience"
- "desc": "The Obzedat ghosts conjure 1d6 [indentured spirits](/3-Mechanics/CLI/bestiary/undead/indentured-spirit-ggr.md)\
    \ (described in this chapter) within 60 feet of one of them."
  "name": "Indentured Spirits (Costs 3 Actions)"
"source":
- "GGR"
"image": "/3-Mechanics/CLI/bestiary/undead/token/obzedat-ghost.png"
```
^statblock

```encounter-table
name: Obzedat Ghost
creatures:
 - 1: Obzedat Ghost
```