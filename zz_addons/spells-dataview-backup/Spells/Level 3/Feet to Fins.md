---
name: Feet to Fins
alias: Feet to Fins
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_3
  - imported/pf2e/school/transmutation
  - imported/pf2e/spelltype/utility
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/primal
level: 3
school: transmutation
type: utility
traditions: [arcane, primal]
deities: Besmara, Dagon, Ragadahn, Seafarer's Hope, Sobek, Ylimancha
spelllist: elemental
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
range: touch
target: 1 willing creature
source: "Pathfinder Core Rulebook"
duration: 10 minutes
traits:
  - common
  - morph
  - transmutation
components:
  - somatic
  - verbal
description: >
  The target's feet transform into fins, improving mobility in the water but reducing it on land. The target gains a swim Speed equal to its normal land Speed, but its land Speed becomes 5 feet.

  &NewLine;**Heightened (6th)** The spell lasts until the next time you make your daily preparations.
---
# `=this.name`
==morph== | ==transmutation==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Deities** `=this.deities`
**Spell List**: `=this.spelllist`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Targets** `=this.target`
**Duration** `=this.duration`

***
`=this.description`