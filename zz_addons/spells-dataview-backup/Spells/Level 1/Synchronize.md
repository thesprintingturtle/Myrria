---
name: Synchronize
alias: Synchronize
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_1
  - imported/pf2e/school/divination
  - imported/pf2e/spelltype/utility
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/divine
  - imported/pf2e/tradition/occult
  - imported/pf2e/tradition/primal
level: 1
school: divination
type: utility
traditions: [arcane, divine, occult, primal]
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
range: touch
target: up to 5 willing creatures
source: "Pathfinder Secrets of Magic"
duration: up to 24 hours
traits:
  - common
  - divination
components:
  - somatic
  - verbal
description: >
  You harmlessly place your unique magic sigil, which is about 1 square inch in size, on your targets. When you Cast the Spell, you set the duration by choosing a time at which point the sigil flashes dimly three times. After that point, the spell ends. Even though spell durations aren't normally exact, the effects of synchronize are precise to the second. The timer is based on the place where the spell was cast, so entering a plane or area where time flows differently changes how the time elapses.

  &NewLine;**Heightened (2nd)** The spell can target up to 20 willing creatures.
---
# `=this.name`
==divination==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Targets** `=this.target`
**Duration** `=this.duration`

***
`=this.description`