---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/ggr
- monster/cr/22
- monster/size/medium
- monster/type/undead
statblock: inline
aliases: ["Jarad Vod Savo"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Guildmasters' Guide to Ravnica p. 235
---
# [Jarad Vod Savo](3-Mechanics\CLI\bestiary\npc/jarad-vod-savo-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 235*  

The Golgari guildmaster is a Devkarin necromancer and lich named Jarad Vod Savo. In life, Jarad was an archer and accomplished hunter, as well as the brother of the previous guildmaster, the ambitious Savra. Jarad mastered the ways of necromancy so he could rise as a lich after he sacrificed himself to save his son from the demon Rakdos.

As head of the Golgari Swarm, Jarad commands elf and medusa assassins, legions of kraul, brutish trolls, and masses of undercity-dwelling creatures. Thanks to the necromantic power he wields-and with the support of his loyal guards and soldiers-he has survived a number of assassination attempts from various upstarts.

## Undead Nature

Jarad doesn't require air, food, drink, or sleep.

```statblock
"name": "Jarad Vod Savo (GGR)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "17"
"hp": !!int "180"
"hit_dice": "24d8 + 72"
"stats":
- !!int "14"
- !!int "16"
- !!int "16"
- !!int "20"
- !!int "16"
- !!int "15"
"speed": "30 ft."
"saves":
  "Wisdom": !!int "10"
  "Intelligence": !!int "12"
  "Constitution": !!int "10"
"skillsaves":
  "Insight": !!int "10"
  "Perception": !!int "10"
  "Arcana": !!int "12"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [exhaustion](/3-Mechanics/CLI/rules/conditions.md#exhaustion), [frightened](/3-Mechanics/CLI/rules/conditions.md#frightened),\
  \ [paralyzed](/3-Mechanics/CLI/rules/conditions.md#paralyzed), [poisoned](/3-Mechanics/CLI/rules/conditions.md#poisoned)"
"senses": "darkvision 120 ft., passive Perception 20"
"languages": "Common, Elvish, Kraul"
"cr": "22"
"traits":
- "desc": "Jarad is a 14th-level Golgari spellcaster. His spellcasting ability is\
    \ Intelligence (spell save DC 20, +12 to hit with spell attacks). Jarad has the\
    \ following wizard spells prepared:\n\nCantrips (at will): [acid splash](/3-Mechanics/CLI/spells/acid-splash.md),\
    \ [chill touch](/3-Mechanics/CLI/spells/chill-touch.md), [mage hand](/3-Mechanics/CLI/spells/mage-hand.md),\
    \ [poison spray](/3-Mechanics/CLI/spells/poison-spray.md), [prestidigitation](/3-Mechanics/CLI/spells/prestidigitation.md)\n\
    \n1st level (4 slots): [entangle](/3-Mechanics/CLI/spells/entangle.md), [ray\
    \ of sickness](/3-Mechanics/CLI/spells/ray-of-sickness.md), [sleep](/3-Mechanics/CLI/spells/sleep.md)\n\
    \n2nd level (3 slots): [Melf's acid arrow](/3-Mechanics/CLI/spells/melfs-acid-arrow.md),\
    \ [ray of enfeeblement](/3-Mechanics/CLI/spells/ray-of-enfeeblement.md), [spider\
    \ climb](/3-Mechanics/CLI/spells/spider-climb.md), [web](/3-Mechanics/CLI/spells/web.md)\n\
    \n3rd level (3 slots): [animate dead](/3-Mechanics/CLI/spells/animate-dead.md),\
    \ [plant growth](/3-Mechanics/CLI/spells/plant-growth.md), [vampiric touch](/3-Mechanics/CLI/spells/vampiric-touch.md)\n\
    \n4th level (3 slots): [blight](/3-Mechanics/CLI/spells/blight.md), [giant\
    \ insect](/3-Mechanics/CLI/spells/giant-insect.md), [grasping vine](/3-Mechanics/CLI/spells/grasping-vine.md)\n\
    \n5th level (2 slots): [cloudkill](/3-Mechanics/CLI/spells/cloudkill.md),\
    \ [insect plague](/3-Mechanics/CLI/spells/insect-plague.md)\n\n6th level (1\
    \ slots): [circle of death](/3-Mechanics/CLI/spells/circle-of-death.md), [create\
    \ undead](/3-Mechanics/CLI/spells/create-undead.md)\n\n7th level (1 slots):\
    \ [finger of death](/3-Mechanics/CLI/spells/finger-of-death.md), [forcecage](/3-Mechanics/CLI/spells/forcecage.md)"
  "name": "spells"
- "desc": "If Jarad fails a saving throw, he can choose to succeed instead."
  "name": "Legendary Resistance (3/Day)"
- "desc": "Jarad has advantage on saving throws against spells and other magical effects."
  "name": "Magic Resistance"
- "desc": "Jarad regains 25 hit points at the start of his turn. If he takes fire\
    \ or radiant damage, this trait doesn't function at the start of his next turn.\
    \ He dies only if he starts its turn with 0 hit points and doesn't regenerate."
  "name": "Regeneration"
- "desc": "Jarad is surrounded by a cloud of spores. As a bonus action, he can cause\
    \ the spores to deal 11 (2d10) poison damage to a creature he can see within\
    \ 10 feet of him."
  "name": "Spore Infusion"
- "desc": "Jarad has advantage on saving throws against any effect that turns undead."
  "name": "Turn Resistance"
- "desc": "If damage reduces Jarad to 0 hit points, he must make a Constitution saving\
    \ throw with a DC of 5 + the damage taken, unless the damage is radiant or from\
    \ a critical hit. On a success, he drops to 1 hit point instead."
  "name": "Undead Fortitude"
"actions":
- "desc": "Jarad makes two attacks: one with his Noxious Touch and one with his Staff\
    \ of Svogthir. He can cast a spell with a casting time of 1 action in place of\
    \ one of these attacks."
  "name": "Multiattack"
- "desc": "Melee Spell Attack: +12 to hit, reach 5 ft., one creature. Hit: 28\
    \ (8d6) poison damage, and the target must succeed on a DC 20 Constitution saving\
    \ throw or be [poisoned](/3-Mechanics/CLI/rules/conditions.md#poisoned) for 1\
    \ minute. The target can repeat the saving throw at the end of each of its turns,\
    \ ending the effect on itself on a success."
  "name": "Noxious Touch"
- "desc": "Melee Weapon Attack: +12 to hit, reach 5 ft., one target. Hit: 12 (2d6\
    \ + 5) bludgeoning damage plus 13 (3d8) poison damage and 13 (3d8) necrotic\
    \ damage."
  "name": "Staff of Svogthir"
"legendary_actions":
- "desc": "Jarad casts one of his cantrips."
  "name": "Cantrip"
- "desc": "Jarad uses Noxious Touch."
  "name": "Noxious Touch (Costs 2 Actions)"
- "desc": "Each creature within 30 feet of Jarad must make a DC 20 Constitution saving\
    \ throw, taking 35 (10d6) necrotic damage on a failed save, or half as much\
    \ damage on a successful one."
  "name": "Disrupt Life (Costs 3 Actions)"
"source":
- "GGR"
"image": "/3-Mechanics/CLI/bestiary/npc/token/jarad-vod-savo.png"
```
^statblock

```encounter-table
name: Jarad Vod Savo
creatures:
 - 1: Jarad Vod Savo
```