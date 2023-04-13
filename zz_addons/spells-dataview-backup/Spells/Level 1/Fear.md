---
name: Fear
alias: Fear
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_1
  - imported/pf2e/school/enchantment
  - imported/pf2e/spelltype/save
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/divine
  - imported/pf2e/tradition/occult
  - imported/pf2e/tradition/primal
level: 1
school: enchantment
type: save
traditions: [arcane, divine, occult, primal]
deities: Dhalavei, Kelizandri
bloodline: demonic
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
range: 30 feet
target: 1 creature
source: "Pathfinder Core Rulebook"
duration: varies
save: will
basic: false
traits:
  - common
  - emotion
  - fear
  - mental
  - enchantment
components:
  - somatic
  - verbal
description: >
  You plant fear in the target; it must attempt a Will save.

  &NewLine;**Critical Success** The target is unaffected.
  &NewLine;**Success** The target is [[Frightened]] 1.
  &NewLine;**Failure** The target is [[Frightened]] 2.
  &NewLine;**Critical Failure** The target is [[Frightened]] 3 and [[Fleeing]] for 1 round.

  &NewLine;**Heightened (3rd)** You can target up to five creatures.
---
# `=this.name`
==emotion== | ==fear== | ==mental== | ==enchantment==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Deities** `=this.deities`
**Bloodline** `=this.bloodline`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Targets** `=this.target`
**Saving Throw** `=this.save`; **Duration** `=this.duration`

***
`=this.description`