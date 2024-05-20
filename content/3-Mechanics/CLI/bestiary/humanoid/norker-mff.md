---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- compendium/src/5e/mff
- monster/cr/1-2
- monster/size/small
- monster/type/humanoid/goblinoid
statblock: inline
aliases: ["Norker"]
NoteIcon: monster
BestiaryType: humanoid (goblinoid)
SourceType: Bestiary
BookSource: Mordenkainen's Fiendish Folio p. 17
---
# [Norker](3-Mechanics\CLI\bestiary\humanoid/norker-mff.md)
*Source: Mordenkainen's Fiendish Folio p. 17*  

Cruel, vicious, and lazy even by the standards of goblinoids, norkers are tough humanoids whose long, sharp fangs and thick, bony exoskeletons make them well-suited to the ranks of hobgoblin armies. Unfortunately for their would-be masters, norkers are rebellious, truculent, and prone to indolence unless watched with a keen eye and a hand that is quick to snap a whip.

## Denizens of the Deep Earth

In the ancient days, norkers were found deep within the earth. They were always few in number, and their god was a cruel, merciless tyrant who kept his children close and the outside world at a distance. This long-lost god may have been Maglubiyet's first conquest and his followers the initial, unwilling recruits into his crusade. Today, hobgoblins chafe at the suggestion that creatures as lazy and untamed as norkers could claim such an honor. For that reason alone, hobgoblin warlords are loath to use these creatures, preferring to keep them around as disposable labor in mines and quarries.

## Nasty, Brutish, and Short

Even goblins bully and harass norkers, as hobgoblins place the norkers at the bottom of the goblinoid ranks, yet the norkers' ferocity, tough hides, and sharp fangs allow them to rise up and defeat goblinoids that underestimate the norkers' strength and ferocity.. For this reason, norkers are likely encountered away from their brethren. Their natural armor and weapons make them dangerous foes even when relegated to menial labor. Only the dictates of Maglubiyet have prevented the hobgoblins from hunting down and exterminating these creatures.

## A Legacy of Hatred

Given their ancient defeat and terrible treatment at the hands of other goblinoids, the norkers have developed a peculiar sect of Maglubiyet worshipper. They call him the Great Scourge and believe that mortal life is a cruel test. Those norkers whose skin can withstand any blow and whose fangs sink deep into their enemies will be shepherded to paradise. To the norkers, all other creatures are enemies. Strong creatures can be mollified with servitude and obsequious begging, while weaker ones are victims for their fangs and clubs.

```statblock
"name": "Norker (MFF)"
"size": "Small"
"type": "humanoid"
"subtype": "goblinoid"
"alignment": "Chaotic Evil"
"ac": !!int "17"
"hp": !!int "16"
"hit_dice": "3d8 + 3"
"stats":
- !!int "13"
- !!int "10"
- !!int "13"
- !!int "8"
- !!int "8"
- !!int "7"
"speed": "30 ft."
"skillsaves":
  "Athletics": !!int "3"
"senses": "darkvision 60 ft., passive Perception 9"
"languages": "Common, Goblin"
"cr": "1/2"
"actions":
- "desc": "The norker makes one mace and one bite attack."
  "name": "Multiattack"
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 4 (1d6\
    \ + 1) piercing damage."
  "name": "Bite"
- "desc": "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 4 (1d6\
    \ + 1) bludgeoning damage."
  "name": "Mace"
"reactions":
- "desc": "If a creature within 5 feet of the norker makes a melee attack against\
    \ it, the norker can use its reaction to cause 4 piercing damage to it."
  "name": "Defensive Rebuke"
"source":
- "MFF"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/norker.png"
```
^statblock

```encounter-table
name: Norker
creatures:
 - 1: Norker
```