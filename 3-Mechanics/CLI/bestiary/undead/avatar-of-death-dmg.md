---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/dmg
- monster/cr/
- monster/size/medium
- monster/type/undead
statblock: inline
aliases: ["Avatar of Death (DMG)"]
NoteIcon: monster
BestiaryType: undead
SourceType: Bestiary
BookSource: Dungeon Master's Guide p. 164, Tasha's Cauldron of Everything. Available in the SRD.
---
# [Avatar of Death (DMG)](3-Mechanics\CLI\bestiary\undead/avatar-of-death-dmg.md)
*Source: Dungeon Master's Guide p. 164, Tasha's Cauldron of Everything. Available in the SRD.*  

Summoned by the "Skull" card from the [Deck of Many Things](/3-Mechanics/CLI/items/deck-of-many-things.md).

```statblock
"name": "Avatar of Death (DMG) (DMG)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "20"
"stats":
- !!int "16"
- !!int "16"
- !!int "16"
- !!int "16"
- !!int "16"
- !!int "16"
"speed": "60 ft., fly 60 ft. (hover)"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/rules/conditions.md#charmed),\
  \ [frightened](/3-Mechanics/CLI/rules/conditions.md#frightened), [paralyzed](/3-Mechanics/CLI/rules/conditions.md#paralyzed),\
  \ [petrified](/3-Mechanics/CLI/rules/conditions.md#petrified), [poisoned](/3-Mechanics/CLI/rules/conditions.md#poisoned),\
  \ [unconscious](/3-Mechanics/CLI/rules/conditions.md#unconscious)"
"senses": "darkvision 60 ft., truesight 60 ft., passive Perception 13"
"languages": "all languages known to its summoner"
"traits":
- "desc": "The avatar can move through other creatures and objects as if they were\
    \ difficult terrain. It takes 5 (1d10) force damage if it ends its turn inside\
    \ an object."
  "name": "Incorporeal Movement"
- "desc": "The avatar is immune to features that turn undead."
  "name": "Turn Immunity"
"actions":
- "desc": "The avatar sweeps its spectral scythe through a creature within 5 feet\
    \ of it, dealing 7 (1d8 + 3) slashing damage plus 4 (1d8) necrotic damage."
  "name": "Reaping Scythe"
"source":
- "DMG"
- "TCE"
- "BMT"
"image": "/3-Mechanics/CLI/bestiary/undead/token/avatar-of-death.png"
```
^statblock

```encounter-table
name: Avatar of Death (DMG)
creatures:
 - 1: Avatar of Death (DMG)
```