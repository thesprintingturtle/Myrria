---
name: Status
alias: Status
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_2
  - imported/pf2e/school/divination
  - imported/pf2e/spelltype/utility
  - imported/pf2e/tradition/divine
  - imported/pf2e/tradition/occult
  - imported/pf2e/tradition/primal
level: 2
school: divination
type: utility
traditions: [divine, occult, primal]
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
range: touch
target: 1 willing living creature
source: "Pathfinder Core Rulebook"
duration: until the next time you make your daily preparations
traits:
  - common
  - detection
  - divination
components:
  - somatic
  - verbal
description: >
  As long as you and the target are on the same plane of existence and both alive, you remain aware of its present state. You know the target's direction from you, distance from you, and any conditions affecting it.

  &NewLine;**Heightened (4th)** The spell's range increases to 30 feet, and you can target up to 10 creatures.
---
# `=this.name`
==detection== | ==divination==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Targets** `=this.target`
**Duration** `=this.duration`

***
`=this.description`