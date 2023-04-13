---
name: Create Water
alias: Create Water
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
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
range: 0 feet
source: "Pathfinder Core Rulebook"
traits:
  - common
  - water
  - conjuration
components:
  - somatic
  - verbal
description: >
  As you cup your hands, water begins to flow forth from them. You create 2 gallons of water. If no one drinks it, it evaporates after 1 day.
---
# `=this.name`
==water== | ==conjuration==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Spell List**: `=this.spelllist`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`

***
`=this.description`