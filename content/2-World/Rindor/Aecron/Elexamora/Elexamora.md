---
NoteIcon: settlement
tags:
  - Category/Settlement
Community-Size: Outpost
Alignment: Lawful Neutral
Government: Oligarchy
type: Settlement
politics: Aristocracy/Tribal
leader: Drabion Watcaster/Phenemion
guildsgroups:
  - Cast of Stelos
  - Family of Watcaster
region:
  - North of Monestro
  - South-East of Mopria
  - Aecron
size: Region
population: 75000
commonraces:
  - Tieflings
  - Centuars
religion:
  - None
exports:
  - Grain
  - Mages
  - Cavelry
imports:
  - Everything Else
defences: Calvary, Mages, Plains Landscape
---
---


> [!infobox]
> # `=this.file.name`
> ![[Elexamora-Reference.webp|cover hsmall]]
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
> [[Monestro]] | 🕓: `VIEW[round((450* {Travel Calculator#TravelCalc}) / 60 / {Travel Calculator#HoursPerDay}, 1)]`      |
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

The home of the Tieflings and the Centaurs they are in an everlasting war with Monestro to reclaim the lands they once saw as theirs. One of the countries not fully enslaved by The Beneath, they do not have a maw in their lands and intend to keep it that way. With a long bitter rivalry between the two dominant races of the country, they never hesitate to band together against their fight against the southern country of Monestro. They are ruled under an Oligarchy.

### Regional Map
![[Elexamora-Regional.jpg]]

### Location Map
![[Elexamora-TribalCouncil.jpg]]

## Notable NPCs
 * Drabion Watcaster 
 * Phenemion, Lance of the Grain

## Groups
- ###### Family of Watcaster
	- The family of Teifling aristocracy, they control the money that flows through Elexamora's crops, tiling the fields and raising the funds for the entire country. While in good terms with the cast of Centaurs, they still find themselves wanting more. Currently the head of the household is a man named Drabion Watcaster who lives in a rural farm directly North of the capital city.

- ###### Cast of Stelos
	- The cast of Centaur honor, they have inhabited these lands far longer then any other race and it shows -- especially in the forests of Elexamora. Brutal fighters, they are the bulk of the calvary as well as the commanders of the countries military might. Far off lands hear tales of heroic bravery which originate here. Born to fight, each Centaur is marked with the cast's emblem (which is two crossed strands of wheat with a lance in the center). The current chief of the cast is a Centaur known only as Phenemion, Lance of the Grain.

## Points of Interest
Unknown to the party.

## Internal Relationships
Antagonistic relationship between the Cast of Stelos and the Family of Watcaster.

## Outward Relationships
Hates Monestro, would rather put aside their own differences to kill Monestro.
