---
name: Quicken Time
alias: Quicken Time
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_5
  - imported/pf2e/school/transmutation
  - imported/pf2e/spelltype/utility
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/occult
level: 5
school: transmutation
type: utility
traditions: [arcane, occult]
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
range: 120 feet
area: 20-foot burst
source: "Pathfinder Dark Archive"
duration: 1 minute
traits:
  - common
  - transmutation
components:
  - somatic
  - verbal
description: >
  You speed up the time stream in an area, stretching and pulling it until time flows swift and wild. Any creature that begins its turn in the area is [[Quickened]] and can use the extra action each round to Stride or Strike. Unfortunately, speeding up time is much more difficult than slowing it down, and the effect is uneven and jittery, making accuracy between times painfully difficult; creatures inside the area are [[Concealed]] to those outside it, and vice versa.
---
# `=this.name`
==transmutation==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Area** `=this.area`
**Duration** `=this.duration`

***
`=this.description`