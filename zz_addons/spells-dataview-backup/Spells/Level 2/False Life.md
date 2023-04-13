---
name: False Life
alias: False Life
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_2
  - imported/pf2e/school/necromancy
  - imported/pf2e/spelltype/utility
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/occult
level: 2
school: necromancy
type: utility
traditions: [arcane, occult]
deities: Osiris, Qi Zhong, Touch of the Sun, Urgathoa
bloodline: undead
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
source: "Pathfinder Core Rulebook"
duration: 8 hours
traits:
  - common
  - necromancy
components:
  - somatic
  - verbal
description: >
  You create a reservoir of vitality from necromantic energy, gaining a number of temporary Hit Points equal to 6 plus your spellcasting ability modifier.

  &NewLine;**Heightened (+1)** The temporary Hit Points increase by 3.
---
# `=this.name`
==necromancy==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Deities** `=this.deities`
**Bloodline** `=this.bloodline`
**Cast** `=this.time` | `=this.components`
**Duration** `=this.duration`

***
`=this.description`