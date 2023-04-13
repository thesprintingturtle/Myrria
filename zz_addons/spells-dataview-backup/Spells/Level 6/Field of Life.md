---
name: Field of Life
alias: Field of Life
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_6
  - imported/pf2e/school/necromancy
  - imported/pf2e/spelltype/heal
  - imported/pf2e/tradition/divine
  - imported/pf2e/tradition/primal
level: 6
school: necromancy
type: heal
traditions: [divine, primal]
lesson: lesson of renewal
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
range: 30 feet
area: 20-foot burst
source: "Pathfinder Core Rulebook"
duration: sustained up to 1 minute
traits:
  - common
  - healing
  - positive
  - necromancy
components:
  - somatic
  - verbal
description: >
  A field of positive energy fills the area, exuding warmth and rejuvenating those within. Each living creature that starts its turn in the area regains 1d8 Hit Points, and any undead creature that starts its turn in the area takes 1d8 positive damage.

  &NewLine;**Heightened (8th)** The healing and damage increase to 1d10.
  &NewLine;**Heightened (9th)** The healing and damage increase to 1d12.
---
# `=this.name`
==healing== | ==positive== | ==necromancy==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Lesson**: `=this.lesson`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Area** `=this.area`
**Duration** `=this.duration`

***
`=this.description`