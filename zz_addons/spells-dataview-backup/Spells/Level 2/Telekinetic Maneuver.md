---
name: Telekinetic Maneuver
alias: Telekinetic Maneuver
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_2
  - imported/pf2e/school/evocation
  - imported/pf2e/spelltype/attack
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/occult
level: 2
school: evocation
type: attack
traditions: [arcane, occult]
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
range: 60 feet
target: 1 creature
source: "Pathfinder Core Rulebook"
traits:
  - common
  - attack
  - force
  - evocation
components:
  - somatic
  - verbal
description: >
  With a rush of telekinetic power, you move a foe or something they carry. You can attempt to Disarm, Shove, or Trip the target using a spell attack roll instead of an Athletics check.
---
# `=this.name`
==attack== | ==force== | ==evocation==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Targets** `=this.target`

***
`=this.description`