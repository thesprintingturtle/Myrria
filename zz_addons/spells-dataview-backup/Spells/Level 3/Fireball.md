---
name: Fireball
alias: Fireball
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_3
  - imported/pf2e/school/evocation
  - imported/pf2e/spelltype/save
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/primal
level: 3
school: evocation
type: save
traditions: [arcane, primal]
deities: Angradd, Chohar, Dahak, Eiseth, Sarenrae, The Freeing Flame, The Prismatic Ray, Walkena
bloodline: elemental, phoenix
spelllist: elemental
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
range: 500 feet
area: 20-foot burst
source: "Pathfinder Core Rulebook"
save: reflex
basic: true
traits:
  - common
  - fire
  - evocation
components:
  - somatic
  - verbal
description: >
  A roaring blast of fire appears at a spot you designate, dealing 6d6 fire damage.

  &NewLine;**Heightened (+1)** The damage increases by 2d6.
---
# `=this.name`
==fire== | ==evocation==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Deities** `=this.deities`
**Bloodline** `=this.bloodline`
**Spell List**: `=this.spelllist`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Area** `=this.area`
**Basic Saving Throw** `=this.save`

***
`=this.description`