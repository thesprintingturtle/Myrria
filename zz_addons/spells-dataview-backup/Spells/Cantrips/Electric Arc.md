---
name: Electric Arc
alias: Electric Arc
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/cantrip_1
  - imported/pf2e/school/evocation
  - imported/pf2e/spelltype/save
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/primal
level: 1
school: evocation
type: save
traditions: [arcane, primal]
mystery: tempest
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
range: 30 feet
target: 1 or 2 creatures
source: "Pathfinder Core Rulebook"
save: reflex
basic: true
traits:
  - common
  - electricity
  - cantrip
  - evocation
components:
  - somatic
  - verbal
description: >
  An arc of lightning leaps from one target to another. You deal electricity damage equal to 1d4 plus your spellcasting ability modifier.

  &NewLine;**Heightened (+1)** The damage increases by 1d4.
---
# `=this.name`
==electricity== | ==cantrip== | ==evocation==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Mystery**: `=this.mystery`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Targets** `=this.target`
**Basic Saving Throw** `=this.save`

***
`=this.description`