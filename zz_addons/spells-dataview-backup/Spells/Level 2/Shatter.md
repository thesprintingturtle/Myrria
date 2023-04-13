---
name: Shatter
alias: Shatter
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_2
  - imported/pf2e/school/evocation
  - imported/pf2e/spelltype/utility
  - imported/pf2e/tradition/occult
  - imported/pf2e/tradition/primal
level: 2
school: evocation
type: utility
traditions: [occult, primal]
deities: Zyphus
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
range: 30 feet
target: 1 unattended object
source: "Pathfinder Core Rulebook"
traits:
  - common
  - sonic
  - evocation
components:
  - somatic
  - verbal
description: >
  A high-frequency sonic attack shatters a nearby object. You deal 2d10 sonic damage to the object, ignoring the object's Hardness if it is 4 or lower.

  &NewLine;**Heightened (+1)** The damage increases by 1d10, and the Hardness the spell ignores increases by 2.
---
# `=this.name`
==sonic== | ==evocation==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Deities** `=this.deities`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Targets** `=this.target`

***
`=this.description`