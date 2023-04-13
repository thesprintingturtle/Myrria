---
name: Slow
alias: Slow
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_3
  - imported/pf2e/school/transmutation
  - imported/pf2e/spelltype/save
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/occult
  - imported/pf2e/tradition/primal
level: 3
school: transmutation
type: save
traditions: [arcane, occult, primal]
deities: Korada, Lorthact, Matravash
bloodline: demonic
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
range: 30 feet
target: 1 creature
source: "Pathfinder Core Rulebook"
duration: 1 minute
save: fortitude
basic: false
traits:
  - common
  - transmutation
components:
  - somatic
  - verbal
description: >
  You dilate the flow of time around the target, slowing its actions.

  &NewLine;**Critical Success** The target is unaffected.
  &NewLine;**Success** The target is [[Slowed]] 1 for 1 round.
  &NewLine;**Failure** The target is [[Slowed]] 1 for 1 minute.
  &NewLine;**Critical Failure** The target is [[Slowed]] 2 for 1 minute.

  &NewLine;**Heightened (6th)** You can target up to 10 creatures.
---
# `=this.name`
==transmutation==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Deities** `=this.deities`
**Bloodline** `=this.bloodline`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Targets** `=this.target`
**Saving Throw** `=this.save`; **Duration** `=this.duration`

***
`=this.description`