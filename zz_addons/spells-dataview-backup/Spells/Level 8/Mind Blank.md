---
name: Mind Blank
alias: Mind Blank
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_8
  - imported/pf2e/school/abjuration
  - imported/pf2e/spelltype/utility
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/occult
level: 8
school: abjuration
type: utility
traditions: [arcane, occult]
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
range: 30 feet
target: 1 creature
source: "Pathfinder Core Rulebook"
duration: until the next time you make your daily preparations
traits:
  - uncommon
  - abjuration
components:
  - somatic
  - verbal
description: >
  Powerful wards hide a creature from divination magic. The target gains a +4 status bonus to saves against mental effects. Mind blank attempts to counteract any detection, revelation, and scrying effects as if its spell level were 1 higher than its actual level. On a success, the divination effect functions normally except that it detects nothing about the target and its possessions. For instance, detect magic would still detect other magic in the area, but not any magic on the target.
---
# `=this.name`
==uncommon== | ==abjuration==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Targets** `=this.target`
**Duration** `=this.duration`

***
`=this.description`