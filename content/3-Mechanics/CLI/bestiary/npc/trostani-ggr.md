---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/18
- monster/size/large
- monster/type/fey
statblock: inline
aliases: ["Trostani"]
NoteIcon: monster
BestiaryType: fey
SourceType: Bestiary
BookSource: Guildmasters' Guide to Ravnica p. 252
---
# [Trostani](3-Mechanics\CLI\bestiary\npc/trostani-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 252*  

The Selesnya guildmaster is an amalgamation of three dryads in body, will, and soul. Each dryad's body extends from a central trunk, so while they possess independent minds, they share a single name-Trostani and a single life force. Usually Trostani communicates the will of the Worldsoul with one voice, but she retains three distinct personalities that embody the three parts of the Selesnyan ideal: order, life, and harmony. In the midst of increasing tensions on Ravnica, the three personalities have recently been at odds over how best to navigate the conclave through such difficult times.

Trostani spends most of her time in the towering tree of Vitu-Ghazi, the Selesnya guildhall. There she communes with Mat'Selesnya and with the dryads who lead individual Selesnya communities across Ravnica.

```statblock
"name": "Trostani (GGR)"
"size": "Large"
"type": "fey"
"alignment": "Neutral Good"
"ac": !!int "17"
"hp": !!int "252"
"hit_dice": "24d10 + 120"
"stats":
- !!int "19"
- !!int "14"
- !!int "20"
- !!int "16"
- !!int "30"
- !!int "25"
"speed": "30 ft."
"saves":
  "Charisma": !!int "13"
  "Wisdom": !!int "16"
  "Constitution": !!int "11"
"skillsaves":
  "Nature": !!int "9"
  "Insight": !!int "16"
  "Perception": !!int "16"
  "Arcana": !!int "9"
  "Persuasion": !!int "13"
"condition_immunities": "[charmed](/3-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [grappled](/3-Mechanics/CLI/rules/conditions.md#grappled)"
"senses": "darkvision 120 ft., passive Perception 26"
"languages": "Common, Druidic, Elvish, Sylvan"
"cr": "18"
"traits":
- "desc": "Trostani's innate spellcasting ability is Wisdom (spell save DC 24). She\
    \ can innately cast the following spells, requiring no material components:\n\n\
    At will: [dispel magic](/3-Mechanics/CLI/spells/dispel-magic.md), [druidcraft](/3-Mechanics/CLI/spells/druidcraft.md)\n\
    \n1/day each: [conjure fey](/3-Mechanics/CLI/spells/conjure-fey.md), [mass\
    \ cure wounds](/3-Mechanics/CLI/spells/mass-cure-wounds.md)\n\n3/day each:\
    \ [bless](/3-Mechanics/CLI/spells/bless.md), [conjure animals](/3-Mechanics/CLI/spells/conjure-animals.md),\
    \ [giant insect](/3-Mechanics/CLI/spells/giant-insect.md), [moonbeam](/3-Mechanics/CLI/spells/moonbeam.md),\
    \ [plant growth](/3-Mechanics/CLI/spells/plant-growth.md), [spike growth](/3-Mechanics/CLI/spells/spike-growth.md),\
    \ [suggestion](/3-Mechanics/CLI/spells/suggestion.md)"
  "name": "innate"
- "desc": "If Trostani fails a saving throw, she can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "Trostani has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "Trostani's weapon attacks are magical."
  "name": "Magic Weapons"
- "desc": "Trostani can communicate with beasts and plants as if they shared a language."
  "name": "Speak with Beasts and Plants"
- "desc": "Once on her turn, Trostani can use 10 feet of her movement to step magically\
    \ into one living tree within her reach and emerge from a second living tree within\
    \ 60 feet of the first tree, appearing in an unoccupied space within 5 feet of\
    \ the second tree. Both trees must be Large or bigger."
  "name": "Tree Stride"
"actions":
- "desc": "Trostani takes three actions: she uses Constrict and Touch of Order, and\
    \ she casts a spell with a casting time of 1 action."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +11 to hit, reach 5 ft., one creature. Hit: 15\
    \ (3d6 + 5) bludgeoning damage, and the target is [grappled](/3-Mechanics/CLI/rules/conditions.md#grappled)\
    \ (escape DC 19). Until this grapple ends, the target is [restrained](/3-Mechanics/CLI/rules/conditions.md#restrained).\
    \ Trostani can grapple no more than three targets at a time."
  "name": "Constrict"
- "desc": "Melee Spell Attack: +16 to hit, reach 5 ft., one creature. Hit: 23\
    \ (3d8 + 10) radiant damage, and Trostani can choose one magic item she can\
    \ see in the target's possession. Unless it's an artifact, the item's magic is\
    \ suppressed until the start of Trostani's next turn."
  "name": "Touch of Order"
- "desc": "Trostani conjures a momentary whirl of branches and vines at a point she\
    \ can see within 60 feet of her. Each creature in a 30-foot cube on that point\
    \ must make a DC 24 Dexterity saving throw, taking 21 (6d6) bludgeoning damage\
    \ and 21 (6d6) slashing damage on a failed save, or half as much damage on a\
    \ successful one."
  "name": "Wrath of Mat'Selesnya (Recharge 5-6)"
"legendary_actions":
- "desc": "Trostani makes one melee attack, with advantage on the attack roll."
  "name": "Voice of Harmony"
- "desc": "Trostani bestows 20 temporary hit points on another creature she can see\
    \ within 120 feet of her."
  "name": "Voice of Life"
- "desc": "Trostani casts [dispel magic](/3-Mechanics/CLI/spells/dispel-magic.md)."
  "name": "Voice of Order"
- "desc": "Trostani casts [suggestion](/3-Mechanics/CLI/spells/suggestion.md). This\
    \ counts as one of her daily uses of the spell."
  "name": "Chorus of the Conclave (Costs 2 Actions)"
- "desc": "Trostani animates one or two trees she can see within 120 feet of her,\
    \ causing them to uproot themselves and become awakened trees (see the Monster\
    \ Manual for their stat blocks) for 1 minute or until Trostani uses a bonus action\
    \ to end the effect. These trees understand Druidic and obey Trostani's spoken\
    \ commands, but can't speak. If she issues no commands to them, the trees do nothing\
    \ but follow her and take the Dodge action."
  "name": "Awaken Grove Guardians (Costs 3 Actions)"
"source":
- "GGR"
"image": "/3-Mechanics/CLI/bestiary/npc/token/trostani.png"
```
^statblock

```encounter-table
name: Trostani
creatures:
 - 1: Trostani
```