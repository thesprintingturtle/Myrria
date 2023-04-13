---
name: Soft Landing
alias: Soft Landing
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_4
  - imported/pf2e/school/abjuration
  - imported/pf2e/spelltype/utility
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/occult
  - imported/pf2e/tradition/primal
level: 4
school: abjuration
type: utility
traditions: [arcane, occult, primal]
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
range: 1 mile
area: 60-foot emanation
source: "Pathfinder Dark Archive"
duration: 1 minute
traits:
  - common
  - abjuration
components:
  - somatic
  - verbal
description: >
  You create a magical field that buoys any creature or object falling into the area, providing a harmless landing from any height. As you generally fall 1,500 feet per round, you can cast this spell while you are falling to ensure a safe landing, provided you can see your landing point and it's within range.
---
# `=this.name`
==abjuration==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Area** `=this.area`
**Duration** `=this.duration`

***
`=this.description`