---
name: Burning Hands
alias: Burning Hands
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_1
  - imported/pf2e/school/evocation
  - imported/pf2e/spelltype/save
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/primal
level: 1
school: evocation
type: save
traditions: [arcane, primal]
deities: Angradd, Chohar, Lady Nanbyo, Moloch, Nurgal, Ra, Rovagug, Sarenrae, Szuriel, Walkena, Ymeri
bloodline: elemental, phoenix
spelllist: elemental
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
area: 15-foot cone
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
  Gouts of flame rush from your hands. You deal 2d6 fire damage to creatures in the area.

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
**Area** `=this.area`
**Basic Saving Throw** `=this.save`

***
`=this.description`