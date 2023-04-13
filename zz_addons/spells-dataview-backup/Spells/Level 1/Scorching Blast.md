---
name: Scorching Blast
alias: Scorching Blast
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_1
  - imported/pf2e/school/evocation
  - imported/pf2e/spelltype/attack
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/occult
  - imported/pf2e/tradition/primal
level: 1
school: evocation
type: attack
traditions: [arcane, occult, primal]
time: 1 action
pf2etime: "*⬻{ .Pathfinder }*"
source: "Pathfinder Kingmaker"
duration: until the end of your turn
traits:
  - rare
  - fire
  - evocation
components:
  - somatic
description: >
  You evoke a mass of fire into the air around your outstretched fist. For the remainder of your turn, you can blast targets within 30 feet with this fire by spending a single action which has the attack and concentrate traits. When you do so, attempt a ranged spell attack roll. If you hit, you inflict 2d8 fire damage. On a critical hit, the target takes 1d6 persistent fire damage.

  &NewLine;**Heightened (+1)** The base damage increases by 1d8 and the persistent fire damage on a critical hit increases by 2.
---
# `=this.name`
==rare== | ==fire== | ==evocation==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Cast** `=this.time` | `=this.components`
**Duration** `=this.duration`

***
`=this.description`