---
name: Air Bubble
alias: Air Bubble
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_1
  - imported/pf2e/school/conjuration
  - imported/pf2e/spelltype/utility
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/divine
  - imported/pf2e/tradition/primal
level: 1
school: conjuration
type: utility
traditions: [arcane, divine, primal]
spelllist: elemental
time: reaction
pf2etime: "*⬲{ .Pathfinder }*"
trigger: A creature within range enters an environment where it can't breathe
range: 60 feet
target: the triggering creature
source: "Pathfinder Core Rulebook"
duration: 1 minute
traits:
  - common
  - air
  - conjuration
components:
  - verbal
description: >
  A bubble of pure air appears around the target's head, allowing it to breathe normally. The effect ends as soon as the target returns to an environment where it can breathe normally.
---
# `=this.name`
==air== | ==conjuration==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Spell List**: `=this.spelllist`
**Cast** `=this.time` | `=this.components`; **Trigger** `=this.trigger`
**Range** `=this.range`; **Targets** `=this.target`
**Duration** `=this.duration`

***
`=this.description`