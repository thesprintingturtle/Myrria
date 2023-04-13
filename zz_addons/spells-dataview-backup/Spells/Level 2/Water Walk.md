---
name: Water Walk
alias: Water Walk
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_2
  - imported/pf2e/school/transmutation
  - imported/pf2e/spelltype/utility
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/divine
  - imported/pf2e/tradition/primal
level: 2
school: transmutation
type: utility
traditions: [arcane, divine, primal]
spelllist: elemental
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
range: touch
target: 1 creature
source: "Pathfinder Core Rulebook"
duration: 10 minutes
traits:
  - common
  - transmutation
components:
  - somatic
  - verbal
description: >
  The target can walk on the surface of water and other liquids without falling through. It can go underwater if it wishes, but in that case it must Swim normally. This spell doesn't grant the ability to breathe underwater.

  &NewLine;**Heightened (4th)** The spell's range increases to 30 feet, the duration increases to 1 hour, and you can target up to 10 creatures.
---
# `=this.name`
==transmutation==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Spell List**: `=this.spelllist`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Targets** `=this.target`
**Duration** `=this.duration`

***
`=this.description`