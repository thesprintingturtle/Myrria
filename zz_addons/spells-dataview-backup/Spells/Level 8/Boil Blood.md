---
name: Boil Blood
alias: Boil Blood
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_8
  - imported/pf2e/school/evocation
  - imported/pf2e/spelltype/save
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/primal
level: 8
school: evocation
type: save
traditions: [arcane, primal]
spelllist: elemental
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
range: 60 feet
target: 1 creature
source: "Pathfinder Secrets of Magic"
save: fortitude
basic: false
traits:
  - common
  - fire
  - evocation
components:
  - somatic
  - verbal
description: >
  You heat a foe's blood and boil it within its veins. The target takes 10d10 fire damage, with a Fortitude save. A nonliving creature with blood in its body (such as a vampire) can be affected, but a creature with no blood is immune.

  &NewLine;**Critical Success** The target is unaffected.
  &NewLine;**Success** The target takes half damage.
  &NewLine;**Failure** The target takes full damage and is [[Drained]] 2.
  &NewLine;**Critical Failure** The target takes double damage and is [[Drained]] 3.

  &NewLine;**Heightened (+1)** The damage increases by 1d10.
---
# `=this.name`
==fire== | ==evocation==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Spell List**: `=this.spelllist`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Targets** `=this.target`
**Saving Throw** `=this.save`

***
`=this.description`