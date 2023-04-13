---
name: Color Spray
alias: Color Spray
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_1
  - imported/pf2e/school/illusion
  - imported/pf2e/spelltype/save
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/occult
level: 1
school: illusion
type: save
traditions: [arcane, occult]
deities: Pulura, Shelyn
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
area: 15-foot cone
source: "Pathfinder Core Rulebook"
duration: 1 or more rounds (see below)
save: will
basic: false
traits:
  - common
  - incapacitation
  - visual
  - illusion
components:
  - somatic
  - verbal
description: >
  Swirling colors affect viewers based on their Will saves.

  &NewLine;**Critical Success** The creature is unaffected.
  &NewLine;**Success** The creature is [[Dazzled]] for 1 round.
  &NewLine;**Failure** The creature is [[Stunned]] 1, [[Blinded]] for 1 round, and Dazzled for 1 minute.
  &NewLine;**Critical Failure** The creature is Stunned for 1 round and Blinded for 1 minute.
---
# `=this.name`
==incapacitation== | ==visual== | ==illusion==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Deities** `=this.deities`
**Cast** `=this.time` | `=this.components`
**Area** `=this.area`
**Saving Throw** `=this.save`; **Duration** `=this.duration`

***
`=this.description`