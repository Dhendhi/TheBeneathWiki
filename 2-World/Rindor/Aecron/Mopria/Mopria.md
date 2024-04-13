---
NoteIcon: settlement
tags:
  - Category/Settlement
Community-Size: Region
Alignment: 
Government: Democracy
type: Region
politics: Republic
leader: Herviet Aunsellius/Collett Klinge
guildsgroups:
  - Moprian Senate
region:
  - Aecron
  - West of Elexamora
  - North of Kurogh Port
size: 200000 sq mi
population: 52000
commonraces:
  - Elves
  - Humans
  - All Races
religion:
  - Church of the Cocoon
  - Cult of the Scar
  - Ancestral Flame
exports:
  - Lumber
  - Stone
  - Literature
imports:
  - Grain
  - Meat
  - Ink
---

> [!infobox]
> # `=this.file.name`
> ![[Mopria-Icon.jpg]]
> ###### Geography
> Type |  Stat |
> ---|---|
> Type | `=this.type` |
> Size | `=this.size` |
> Region | `=this.region` |
> ###### Travel (`=[[Travel Calculator]].HoursPerDay` hrs per day)
> ###### [[Travel Calculator]]  / [[Exhaustion]]:  `=[[Travel Calculator]].ExhaustionLevel`
> Destination |  Travel Days  |
> ---|---|
> [[Monestro]] | 🕓: `VIEW[round((1067* {Travel Calculator#TravelCalc}) / 60 / {Travel Calculator#HoursPerDay}, 1)]`      |
> [[Elexamora]] | 🕓: `VIEW[round((703* {Travel Calculator#TravelCalc}) / 60 / {Travel Calculator#HoursPerDay}, 1)]`      |
> ###### Politics
> Type |  Stat |
> ---|---|
> Govt Type | `=this.politics` |
> Ruler | `=this.leader` |
> Defense | `=this.defences` |
> ###### Society
> Type |  Stat |
> ---|---|
> Population | `=this.population` |
> Races | `=this.commonraces` |
> Temples | `=this.religion`  |
> ###### Commerce
> Type |  Stat |
> ---|---|
> Exports | `=this.exports` |
> Imports | `=this.imports` |
> ###### Organizations
> Type |  Stat |
> ---|---|
> ```dataview
table WITHOUT ID link(file.name) AS "Group", link(Leader) AS "Leader"
where contains( PrimaryHome, this.file.name)


# `=this.file.name`

## Overview
Mopria is the most politically diverse nation on the continent of Aecron, as they are the first democratically ruled nation on the realm. After their revolution against the ruling class 300 years prior, the people have risen up and claimed those now laid positions of power. They rule with the commoner in mind, and thus the standard of living is the dream of most peasant farmers in other nations. While being democratic however, they have have very zealous worshiper from the Church of the Cocoon which believe in the butterfly Aecron (from which the continent was named).

### Small Regional Map
![[Mopria-Map.jpg]]

### Regional Picture
![[Mopria-Picture.jpg]]

## Notable NPCs

#### Herviet Aunsellius
The leader of the conservative faction in the Senate, they are the champions of the aristocracy. They are a rich half-elf in the running for Primus in the Senate.

#### Collett Klinge
The leader of the progressive faction in the Senate, they are the champions of the people. Collett is an Elf who was born into the Church before deciding to leave and join local government. They have since rose through the ranks, earning countless voters with their changes to improve the lifestyle of the commoner.

## Points of Interest

##### Ivory Crags
The Ivory Crags are a set of mountains on the coast of the Northern side of the country. They provide a nearly impassible semi-circle around the village Voscal held by the Eladrin, an unoccupied territory of Mopria.

## Internal Relationships
The conservative and progressive factions are in an ideological war in the Senate, wrestling for control of government.

## Outward Relationships
Mopria and [[Kurogh Port]] have had a sour relationship ever since [[Kurogh Port]] attempted to declare their own independence. Mopria still believes that the Port is under their control, and their maps show it as part of the country.
Mopria and Voscal's relationship is tenuous at best. They don't interact much due to the natural barrier between them, however Mopria also believes Voscal to be under their control and thus needing to pay taxes to them, which Voscal vehemently disagrees with.

