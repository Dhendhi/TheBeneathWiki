---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mff
- monster/cr/3
- monster/size/medium
- monster/type/fey
statblock: inline
aliases: ["Forlarren"]
NoteIcon: monster
BestiaryType: fey
SourceType: Bestiary
BookSource: Mordenkainen's Fiendish Folio p. 9
---
# [Forlarren](3-Mechanics\CLI\bestiary\fey/forlarren-mff.md)
*Source: Mordenkainen's Fiendish Folio p. 9*  

The descendants of satyrs corrupted by infernal power, forlarren are miserable creatures—an unhappy union between the rigid demands of the Nine Hells and the impulsive hedonism of the Feywild. Driven by dramatic and unpredictable emotions, these feral creatures wreak havoc wherever they go.

## Corrupted Essence

The devils of Avernus attempted an expedition to the Feywild long ago, and the forlarren are the bitter reminder of that doomed excursion. The archdevil Fierna—co-ruler of Phlegethos, the fourth layer of the Nine Hells—courted a mighty fey in hopes of luring him into trading away his soul. The attempt failed, but not before a troop of satyrs were corrupted by the dark delights of Phlegethos. The satyrs were bound to their fey lord and unable to bargain away their souls. So rather than claim them, Fierna warped and twisted them before returning them to the Feywild, content that the corruption of the satyrs would be adequate compensation for her failure.

## Bifurcated Souls

The divided nature of the forlarren reflects their origin, marking each one as two entities trapped in a single form. One forlarren might present itself as a friendly, agreeable guide that helps travelers survive the Nine Hells. Another is a howling beast that attempts to destroy all in its path. One will show mercy and empathy peppered with a parental attitude toward strangers. Another is a mirthful sybarite with an unfettered love of food, drink, and romance. When dealing with the forlarren, the only constant is the malleable, chaotic, and temperamental nature they all share.

When its diabolical aspect shines through, a forlarren is a cunning, calculating, and brutal enemy. It might use its natural charm to worm its way into earning trust from those it encounters, casting itself as a helpless creature pleading for aid even as it looks for the opportunity to betray and overpower. Or it might seek to dominate the weak, set itself up as a petty lord, and rule over all those who fall into its grasp.

## A Sinister Cycle

A forlarren in its fey aspect demonstrates self-destructive urges that reflect the inherent tension in its nature. That aspect might drive it to drink itself nearly to death, or to throw itself into caring for others with such relentless energy that it eventually collapses from [exhaustion](conditions.md#exhaustion). Unfortunately, when it reaches that breaking point, its diabolical nature asserts itself, and it remains in this scheming, dominating mindset until its plans are foiled and it faces defeat. Then, overwhelmed with fear and shame, the forlarren's diabolical nature fades and its fey aspect emerges once again.

Several ballads of the Feywild recount the dramatic fall of valiant forlarren. In all these tales, the hero achieves some great deed only to see their sinister, diabolical side surface. Deceiving their companions during their most daunting trials, the forlarren then betrays those companions at the worst moment possible.

```statblock
"name": "Forlarren (MFF)"
"size": "Medium"
"type": "fey"
"alignment": "Chaotic Neutral"
"ac": !!int "16"
"hp": !!int "45"
"hit_dice": "6d8 + 18"
"stats":
- !!int "14"
- !!int "16"
- !!int "17"
- !!int "12"
- !!int "11"
- !!int "18"
"speed": "40 ft."
"skillsaves":
  "Deception": !!int "8"
  "Stealth": !!int "5"
  "Acrobatics": !!int "5"
"senses": "darkvision 30 ft., passive Perception 10"
"languages": "Common, Sylvan"
"cr": "3"
"traits":
- "desc": "The forlarren's innate spellcasting ability is Charisma (spell save DC\
    \ 14). It can innately cast the following spells, requiring no material components:\n\
    \nAt will: [expeditious retreat](/3-Mechanics/CLI/spells/expeditious-retreat.md),\
    \ [false life](/3-Mechanics/CLI/spells/false-life.md), [minor illusion](/3-Mechanics/CLI/spells/minor-illusion.md),\
    \ [prestidigitation](/3-Mechanics/CLI/spells/prestidigitation.md)\n\n1/day each:\
    \ [heal](/3-Mechanics/CLI/spells/heal.md), [heat metal](/3-Mechanics/CLI/spells/heat-metal.md),\
    \ [mirror image](/3-Mechanics/CLI/spells/mirror-image.md)\n\n3/day each: [aid](/3-Mechanics/CLI/spells/aid.md),\
    \ [misty step](/3-Mechanics/CLI/spells/misty-step.md), [Tasha's hideous laughter](/3-Mechanics/CLI/spells/tashas-hideous-laughter.md)"
  "name": "innate"
- "desc": "The forlarren has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
"actions":
- "desc": "The forlarren makes two claw attacks and one gore attack, or it makes three\
    \ chromatic ray attacks."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) slashing damage."
  "name": "Claw"
- "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) piercing damage."
  "name": "Gore"
- "desc": "Ranged Spell Attack: +6 to hit, range 60 ft., one target. Hit: 3 (1d6)\
    \ lightning damage plus 3 (1d6) fire damage plus 3 (1d6) cold damage."
  "name": "Chromatic Ray"
"source":
- "MFF"
"image": "/3-Mechanics/CLI/bestiary/fey/token/forlarren.png"
```
^statblock

```encounter-table
name: Forlarren
creatures:
 - 1: Forlarren
```