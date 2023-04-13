---
name: Gravitational Pull
alias: Gravitational Pull
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_1
  - imported/pf2e/school/evocation
  - imported/pf2e/spelltype/save
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/occult
level: 1
school: evocation
type: save
traditions: [arcane, occult]
time: 1 to 3
pf2etime: ""
range: 30 feet
target: 1 creature
source: "Pathfinder Secrets of Magic"
save: fortitude
basic: false
traits:
  - common
  - evocation
components:
description: >
  By suddenly altering gravity, you pull the target toward you. The target is pulled 10 feet closer to you unless it succeeds at a Fortitude save. On a critical failure, it's also knocked [[Prone]]. The effects of this spell change depending on the number of actions you spend when you Cast this Spell.
  1 (somatic) The spell targets one creature.
  2 (somatic, verbal) The spell targets one creature and pulls the target 20 feet instead of 10.
  3 (material, somatic, verbal) The spell targets up to 5 creatures.
---
# `=this.name`
==evocation==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Targets** `=this.target`
**Saving Throw** `=this.save`

***
`=this.description`