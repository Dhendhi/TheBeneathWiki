---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mgelft
- monster/cr/2
- monster/size/small
- monster/type/humanoid/grung
statblock: inline
aliases: ["King Robbit the Slimy"]
NoteIcon: monster
BestiaryType: humanoid (Grung)
SourceType: Bestiary
BookSource: Muk's Guide To Everything He Learned From Tasha p. 32
---
# [King Robbit the Slimy](3-Mechanics\CLI\bestiary\humanoid/king-robbit-the-slimy-mgelft.md)
*Source: Muk's Guide To Everything He Learned From Tasha p. 32*  

King Robbit has a tiny pet snail whom he adores. Maybe if you bring the snail their favorite snack or toy, King Robbit will be willing to help!

```statblock
"name": "King Robbit the Slimy (MGELFT)"
"size": "Small"
"type": "humanoid"
"subtype": "Grung"
"alignment": "lawful grumpy"
"ac": !!int "13"
"hp": !!int "27"
"hit_dice": "5d6 + 10"
"stats":
- !!int "7"
- !!int "16"
- !!int "15"
- !!int "10"
- !!int "11"
- !!int "15"
"speed": "25 ft., climb 25 ft."
"saves":
  "Dexterity": !!int "5"
"skillsaves":
  "Intimidation": !!int "4"
  "Athletics": !!int "2"
  "Stealth": !!int "5"
  "Perception": !!int "2"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [poisoned](/3-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "passive Perception 12"
"languages": "Grung"
"cr": "2"
"traits":
- "desc": "The grung can breathe air and water."
  "name": "Amphibious"
- "desc": "Any creature that grapples the grung or otherwise comes into direct contact\
    \ with the grung's skin must succeed on a DC 12 Constitution saving throw or become\
    \ [poisoned](/3-Mechanics/CLI/rules/conditions.md#poisoned) for 1 minute. A [poisoned](/3-Mechanics/CLI/rules/conditions.md#poisoned)\
    \ creature no longer in direct contact with the grung can repeat the saving throw\
    \ at the end of each of its turns, ending the effect on itself on a success."
  "name": "Poisonous Skin"
- "desc": "The grung's long jump is up to 25 feet and its high jump is up to 15 feet,\
    \ with or without a running start."
  "name": "Standing Leap"
"actions":
- "desc": "A ferocious gurgling issues from the throat of the Dankwood grung, warning\
    \ those within 15 feet that they are indeed grumpy. Creatures in that area must\
    \ succeed at a DC 12 Charisma saving throw or be [frightened](/3-Mechanics/CLI/rules/conditions.md#frightened)\
    \ until the end of their next turn."
  "name": "Grumpy Grung Growl."
- "desc": "Melee or Ranged Weapon Attack: +0 to hit, reach 5 ft. or range 20/60\
    \ ft., one target. Hit: 3 (1d4 + 1) piercing damage in melee, or 3 (1d4 +\
    \ 1) piercing damage at range. Target must succeed on a DC 12 Constitution saving\
    \ throw or take 5 (2d4) poison damage."
  "name": "Dagger"
- "desc": "Ranged Weapon Attack: +5 to hit, range 80/320 ft., one target. Hit:\
    \ 9 (1d6 + 6) piercing damage. Target must succeed on a DC 12 Constitution saving\
    \ throw or take 5 (2d4) poison damage."
  "name": "Shortbow"
"source":
- "MGELFT"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/king-robbit-the-slimy.png"
```
^statblock

```encounter-table
name: King Robbit the Slimy
creatures:
 - 1: King Robbit the Slimy
```