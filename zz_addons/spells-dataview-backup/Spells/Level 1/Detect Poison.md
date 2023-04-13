---
name: Detect Poison
alias: Detect Poison
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_1
  - imported/pf2e/school/divination
  - imported/pf2e/spelltype/utility
  - imported/pf2e/tradition/divine
  - imported/pf2e/tradition/primal
level: 1
school: divination
type: utility
traditions: [divine, primal]
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
range: 30 feet
target: 1 object or creature
source: "Pathfinder Core Rulebook"
traits:
  - uncommon
  - detection
  - divination
components:
  - somatic
  - verbal
description: >
  You detect whether a creature is venomous or poisonous, or if an object is poison or has been poisoned. You do not ascertain whether the target is poisonous in multiple ways, nor do you learn the type or types of poison. Certain substances, like lead and alcohol, are poisons and so mask other poisons.

  &NewLine;**Heightened (2nd)** You learn the number and types of poison.
---
# `=this.name`
==uncommon== | ==detection== | ==divination==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Targets** `=this.target`

***
`=this.description`