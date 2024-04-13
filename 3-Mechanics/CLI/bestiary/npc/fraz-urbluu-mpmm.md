---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mpmm
- monster/cr/23
- monster/size/large
- monster/type/fiend/demon
statblock: inline
aliases: ["Fraz-Urb'luu"]
NoteIcon: monster
BestiaryType: fiend (demon)
SourceType: Bestiary
BookSource: Mordenkainen Presents: Monsters of the Multiverse p. 129, Mordenkainen's Tome of Foes p. 146
---
# [Fraz-Urb'luu](3-Mechanics\CLI\bestiary\npc/fraz-urbluu-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 129, Mordenkainen's Tome of Foes p. 146*  

Fraz-Urb'luu is the Prince of [Deception](/3-Mechanics/CLI/rules/skills.md#Deception) and Demon Lord of Illusions. He uses every trick, every ounce of demonic cunning, to manipulate his enemies—mortal and Fiend alike—to do his will. Fraz-Urb'luu can create dreamlands and mind-bending fantasies able to deceive the most discerning foes.

Once imprisoned for centuries below Castle Greyhawk on the world of Oerth, Fraz-Urb'luu has slowly rebuilt his power in the Abyss. He seeks the pieces of the legendary [staff of power](/3-Mechanics/CLI/items/staff-of-power.md) taken from him by those who imprisoned him and commands his servants to do likewise.

The Prince of [Deception](/3-Mechanics/CLI/rules/skills.md#Deception)'s true form is like that of a great gargoyle, some 12 feet tall, with an extended, muscular neck; a smiling face framed by long, pointed ears and lank, dark hair; and bat-like wings are furled against his powerful shoulders. He can assume other forms, however, from the hideous to the beautiful.

Many of the cultists of Fraz-Urb'luu aren't even aware they serve the Prince of [Deception](/3-Mechanics/CLI/rules/skills.md#Deception), believing their master is a beneficent being and granter of wishes, some lost god or Celestial, or even another Fiend. Fraz-Urb'luu wears all these masks and more. He particularly delights in aiding demon-hunters against his demonic adversaries, driving the hunters to greater and greater atrocities in the name of their cause, only to eventually reveal his true nature and claim their souls as his own.

## Cultists of Fraz-Urb'luu

> [!note]
> See the Cult of Fraz-Urb'luu entry.

## Fraz-Urb'luu's Lair

Fraz-Urb'luu's lair lies within the abyssal realm of Hollow's Heart, a plain of white dust with few structures on it. The lair itself is the city of Zoragmelok, a circular fortress surrounded by adamantine walls topped with razors and hooks. Corkscrew towers loom above twisted domes and vast amphitheaters, forming a surreal and disorienting cityscape.

The challenge rating of Fraz-Urb'luu is 24 (62,000 XP) when he's encountered in his lair.

```statblock
"name": "Fraz-Urb'luu (MPMM)"
"size": "Large"
"type": "fiend"
"subtype": "demon"
"alignment": "Chaotic Evil"
"ac": !!int "18"
"hp": !!int "337"
"hit_dice": "27d10 + 189"
"stats":
- !!int "29"
- !!int "12"
- !!int "25"
- !!int "26"
- !!int "24"
- !!int "26"
"speed": "40 ft., fly 40 ft."
"saves":
  "Dexterity": !!int "8"
  "Wisdom": !!int "14"
  "Intelligence": !!int "15"
  "Constitution": !!int "14"
"skillsaves":
  "Deception": !!int "15"
  "Stealth": !!int "8"
  "Perception": !!int "14"
"damage_resistances": "cold, fire, lightning"
"damage_immunities": "poison; bludgeoning, piercing, slashing that is nonmagical"
"condition_immunities": "[charmed](/3-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/3-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/3-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [poisoned](/3-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "truesight 120 ft., passive Perception 24"
"languages": "all, telepathy 120 ft."
"cr": "23"
"traits":
- "desc": "Fraz-Urb'luu casts one of the following spells, requiring no material components\
    \ and using Charisma as the spellcasting ability (spell save DC 23):\n\nAt will:\
    \ [alter self](/3-Mechanics/CLI/spells/alter-self.md) (can become Medium when\
    \ changing his appearance), [detect magic](/3-Mechanics/CLI/spells/detect-magic.md),\
    \ [dispel magic](/3-Mechanics/CLI/spells/dispel-magic.md), [phantasmal force](/3-Mechanics/CLI/spells/phantasmal-force.md)\n\
    \n1/day each: [modify memory](/3-Mechanics/CLI/spells/modify-memory.md), [project\
    \ image](/3-Mechanics/CLI/spells/project-image.md)\n\n3/day each: [mislead](/3-Mechanics/CLI/spells/mislead.md),\
    \ [programmed illusion](/3-Mechanics/CLI/spells/programmed-illusion.md), [seeming](/3-Mechanics/CLI/spells/seeming.md)"
  "name": "spells"
- "desc": "If Fraz-Urb'luu fails a saving throw, he can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "Fraz-Urb'luu has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "Fraz-Urb'luu can't be targeted by divination magic, perceived through magical\
    \ scrying sensors, or detected by abilities that sense demons or Fiends."
  "name": "Undetectable"
"actions":
- "desc": "Fraz-Urb'luu makes one Bite attack and two Fist attacks, and he uses Phantasmal\
    \ Terror."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +16 to hit, reach 10 ft., one target. Hit: 19\
    \ (3d6 + 9) force damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +16 to hit, reach 10 ft., one target. Hit: 22\
    \ (3d8 + 9) force damage."
  "name": "Fist"
- "desc": "Fraz-Urb'luu targets one creature he can see within 120 feet of him. The\
    \ target must succeed on a DC 23 Wisdom saving throw, or it takes 16 (3d10)\
    \ psychic damage and is [frightened](/3-Mechanics/CLI/rules/conditions.md#frightened)\
    \ of Fraz-Urb'luu until the end of its next turn."
  "name": "Phantasmal Terror"
"legendary_actions":
- "desc": "Melee Weapon Attack: +16 to hit, reach 15 ft., one target. Hit: 20\
    \ (2d10 + 9) force damage. If the target is a Large or smaller creature, it\
    \ is also [grappled](/3-Mechanics/CLI/rules/conditions.md#grappled) (escape DC\
    \ 24), and it is [restrained](/3-Mechanics/CLI/rules/conditions.md#restrained)\
    \ until the grapple ends. Fraz-Urb'luu can grapple only one creature with his\
    \ tail at a time."
  "name": "Tail"
- "desc": "Fraz-Urb'luu uses Phantasmal Terror."
  "name": "Terror (Costs 2 Actions)"
"source":
- "MPMM"
- "MTF"
"image": "/3-Mechanics/CLI/bestiary/npc/token/fraz-urbluu.png"
```
^statblock

```encounter-table
name: Fraz-Urb'luu
creatures:
 - 1: Fraz-Urb'luu
```