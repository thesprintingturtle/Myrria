---
name: Remove Fear
alias: Remove Fear
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_2
  - imported/pf2e/school/enchantment
  - imported/pf2e/spelltype/utility
  - imported/pf2e/tradition/divine
  - imported/pf2e/tradition/occult
  - imported/pf2e/tradition/primal
level: 2
school: enchantment
type: utility
traditions: [divine, occult, primal]
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
range: touch
target: 1 creature
source: "Pathfinder Core Rulebook"
traits:
  - common
  - enchantment
components:
  - somatic
  - verbal
description: >
  With a touch, you ease a creature's fears. You can attempt to counteract a single fear effect that the target suffers from. This frees only the target, not any other creatures under the fear effect.

  &NewLine;**Heightened (6th)** The spell's range increases to 30 feet, and you can target up to 10 creatures.
---
# `=this.name`
==enchantment==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Targets** `=this.target`

***
`=this.description`