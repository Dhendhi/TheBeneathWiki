---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/26
- monster/size/gargantuan
- monster/type/dragon
statblock: inline
aliases: ["Niv-Mizzet"]
NoteIcon: monster
BestiaryType: dragon
SourceType: Bestiary
BookSource: Guildmasters' Guide to Ravnica p. 241
---
# [Niv-Mizzet](3-Mechanics\CLI\bestiary\npc/niv-mizzet-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 241*  

Possessed of arrogance and vanity that matches his vast intellect and tremendous power, Niv-Mizzet is the ancient dragon who founded and continues to control the Izzet League. From his private laboratory at the top of the Izzet guildhall, Niv-Mizzet directs the research and experiments of his countless underlings. He coordinates a tremendous number of apparently unrelated projects, working toward some mysterious end.

There can be little doubt that this ancient dragon is one of the most intelligent beings on Ravnica and one of the world's most powerful spellcasters. He is just as acquisitive as any dragon, but his treasure is scientific and magical knowledge. His ambition is a looming threat in the minds of all the other guildmasters, but confronting him directly is almost unthinkable thanks to the combination of his awesome magical power and the sheer physical threat of a fire-breathing, swordtoothed dragon.

```statblock
"name": "Niv-Mizzet (GGR)"
"size": "Gargantuan"
"type": "dragon"
"alignment": "Chaotic Neutral"
"ac": !!int "22"
"hp": !!int "370"
"hit_dice": "19d20 + 171"
"stats":
- !!int "29"
- !!int "14"
- !!int "29"
- !!int "30"
- !!int "17"
- !!int "25"
"speed": "40 ft., climb 30 ft., fly 80 ft."
"saves":
  "Wisdom": !!int "11"
  "Intelligence": !!int "18"
  "Constitution": !!int "17"
"skillsaves":
  "Insight": !!int "11"
  "Perception": !!int "11"
  "Arcana": !!int "18"
"damage_resistances": "cold, psychic, thunder"
"damage_immunities": "fire, lightning"
"condition_immunities": "[charmed](/3-Mechanics/CLI/rules/conditions.md#charmed)"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 21"
"languages": "Common, Draconic"
"cr": "26"
"traits":
- "desc": "Niv-Mizzet is a 20th-level Izzet spellcaster. His spellcasting ability\
    \ is Intelligence (spell save DC 26, +18 to hit with spell attacks). He has the\
    \ following wizard spells prepared:\n\nCantrips (at will): [fire bolt](/3-Mechanics/CLI/spells/fire-bolt.md),\
    \ [light](/3-Mechanics/CLI/spells/light.md), [prestidigitation](/3-Mechanics/CLI/spells/prestidigitation.md),\
    \ [ray of frost](/3-Mechanics/CLI/spells/ray-of-frost.md), [shocking grasp](/3-Mechanics/CLI/spells/shocking-grasp.md)\n\
    \n1st level (4 slots): [detect magic](/3-Mechanics/CLI/spells/detect-magic.md),\
    \ [magic missile](/3-Mechanics/CLI/spells/magic-missile.md), [shield](/3-Mechanics/CLI/spells/shield.md),\
    \ [thunderwave](/3-Mechanics/CLI/spells/thunderwave.md), [unseen servant](/3-Mechanics/CLI/spells/unseen-servant.md)\n\
    \n2nd level (3 slots): [blur](/3-Mechanics/CLI/spells/blur.md), [enlarge/reduce](/3-Mechanics/CLI/spells/enlarge-reduce.md),\
    \ [flaming sphere](/3-Mechanics/CLI/spells/flaming-sphere.md), [hold person](/3-Mechanics/CLI/spells/hold-person.md),\
    \ [scorching ray](/3-Mechanics/CLI/spells/scorching-ray.md)\n\n3rd level (3\
    \ slots): [counterspell](/3-Mechanics/CLI/spells/counterspell.md), [fireball](/3-Mechanics/CLI/spells/fireball.md),\
    \ [lightning bolt](/3-Mechanics/CLI/spells/lightning-bolt.md), [slow](/3-Mechanics/CLI/spells/slow.md)\n\
    \n4th level (3 slots): [confusion](/3-Mechanics/CLI/spells/confusion.md),\
    \ [dimension door](/3-Mechanics/CLI/spells/dimension-door.md), [fabricate](/3-Mechanics/CLI/spells/fabricate.md)\n\
    \n5th level (2 slots): [conjure elemental](/3-Mechanics/CLI/spells/conjure-elemental.md),\
    \ [polymorph](/3-Mechanics/CLI/spells/polymorph.md), [wall of fire](/3-Mechanics/CLI/spells/wall-of-fire.md),\
    \ [wall of force](/3-Mechanics/CLI/spells/wall-of-force.md)\n\n6th level (1\
    \ slots): [chain lightning](/3-Mechanics/CLI/spells/chain-lightning.md), [disintegrate](/3-Mechanics/CLI/spells/disintegrate.md),\
    \ [true seeing](/3-Mechanics/CLI/spells/true-seeing.md)\n\n7th level (1 slots):\
    \ [project image](/3-Mechanics/CLI/spells/project-image.md), [reverse gravity](/3-Mechanics/CLI/spells/reverse-gravity.md),\
    \ [teleport](/3-Mechanics/CLI/spells/teleport.md)\n\n8th level (1 slots):\
    \ [control weather](/3-Mechanics/CLI/spells/control-weather.md), [maze](/3-Mechanics/CLI/spells/maze.md),\
    \ [power word stun](/3-Mechanics/CLI/spells/power-word-stun.md)\n\n9th level\
    \ (1 slots): [prismatic wall](/3-Mechanics/CLI/spells/prismatic-wall.md)"
  "name": "spells"
- "desc": "If Niv-Mizzet fails a saving throw, he can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "Niv-Mizzet can maintain [concentration](/3-Mechanics/CLI/rules/conditions.md#concentration)\
    \ on two different spells at the same time. In addition, he has advantage on saving\
    \ throws to maintain [concentration](/3-Mechanics/CLI/rules/conditions.md#concentration)\
    \ on spells."
  "name": "Locus of the Firemind"
- "desc": "Niv-Mizzet has advantage on saving throws against spells and other magical\
    \ effects."
  "name": "Magic Resistance"
- "desc": "When Niv-Mizzet casts a spell that deals damage, he can change the spell's\
    \ damage to cold, fire, force, lightning, or thunder."
  "name": "Master Chemister"
"actions":
- "desc": "Niv-Mizzet makes three attacks: one with his bite and two with his claws."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +17 to hit, reach 15 ft., one target. Hit: 18\
    \ (2d8 + 9) piercing damage plus 14 (4d6) fire damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +17 to hit, reach 10 ft., one target. Hit: 14\
    \ (2d4 + 9) slashing damage."
  "name": "Claw"
- "desc": "Melee Weapon Attack: +17 to hit, reach 20 ft., one target. Hit: 16\
    \ (2d6 + 9) bludgeoning damage."
  "name": "Tail"
- "desc": "Niv-Mizzet exhales fire in a 90-foot cone. Each creature in that area must\
    \ make a DC 25 Dexterity saving throw, taking 91 (26d6) fire damage on a failed\
    \ save, or half as much damage on a successful one."
  "name": "Fire Breath (Recharge 5-6)"
"legendary_actions":
- "desc": "Niv-Mizzet casts one of his cantrips."
  "name": "Cantrip"
- "desc": "Niv-Mizzet makes a tail attack."
  "name": "Tail Attack"
- "desc": "Niv-Mizzet beats his wings. Each creature within 15 feet of him must succeed\
    \ on a DC 25 Dexterity saving throw or take 14 (2d4 + 9) bludgeoning damage\
    \ and be knocked [prone](/3-Mechanics/CLI/rules/conditions.md#prone). Niv-Mizzet\
    \ can then fly up to half his flying speed."
  "name": "Wing Attack (Costs 2 Actions)"
- "desc": "Niv-Mizzet regains a spell slot of 3rd level or lower."
  "name": "Dracogenius (Costs 3 Actions)"
"source":
- "GGR"
"image": "/3-Mechanics/CLI/bestiary/npc/token/niv-mizzet.png"
```
^statblock

```encounter-table
name: Niv-Mizzet
creatures:
 - 1: Niv-Mizzet
```