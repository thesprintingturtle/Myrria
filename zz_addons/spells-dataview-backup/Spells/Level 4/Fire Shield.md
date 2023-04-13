---
name: Fire Shield
alias: Fire Shield
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_4
  - imported/pf2e/school/evocation
  - imported/pf2e/spelltype/utility
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/primal
level: 4
school: evocation
type: utility
traditions: [arcane, primal]
deities: Atreia, Chohar, Folgrit, Iomedae, Milani, Ragathiel, Sorrow's Sword, The Godclaw
spelllist: elemental
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
source: "Pathfinder Core Rulebook"
duration: 1 minute
traits:
  - common
  - fire
  - evocation
components:
  - somatic
  - verbal
description: >
  You wreathe yourself in ghostly flames, gaining cold resistance 5. Additionally, adjacent creatures that hit you with a melee attack, as well as creatures that touch you or hit you with an unarmed attack, take 2d6 fire damage each time they do.

  &NewLine;**Heightened (+2)** The cold resistance increases by 5, and the fire damage increases by 1d6.
---
# `=this.name`
==fire== | ==evocation==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Deities** `=this.deities`
**Spell List**: `=this.spelllist`
**Cast** `=this.time` | `=this.components`
**Duration** `=this.duration`

***
`=this.description`