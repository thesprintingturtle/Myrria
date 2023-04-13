---
name: Guiding Star
alias: Guiding Star
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_2
  - imported/pf2e/school/divination
  - imported/pf2e/spelltype/utility
  - imported/pf2e/tradition/divine
  - imported/pf2e/tradition/primal
level: 2
school: divination
type: utility
traditions: [divine, primal]
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
range: planetary
target: 1 creature you've met
source: "Pathfinder Secrets of Magic"
duration: until your next daily preparations
traits:
  - common
  - detection
  - mental
  - divination
components:
  - somatic
  - verbal
description: >
  You call on the constellations of the night sky to guide a creature to the location where you Cast the Spell. Each time the target views the stars, it receives a mental nudge toward your chosen location, though it isn't compelled to follow. The target can recognize you as the source. If the creature goes to another planet or plane, the spell's effects are suppressed, but they resume if the creature returns.
---
# `=this.name`
==detection== | ==mental== | ==divination==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Targets** `=this.target`
**Duration** `=this.duration`

***
`=this.description`