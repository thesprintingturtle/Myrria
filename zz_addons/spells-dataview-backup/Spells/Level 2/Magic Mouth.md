---
name: Magic Mouth
alias: Magic Mouth
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_2
  - imported/pf2e/school/illusion
  - imported/pf2e/spelltype/utility
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/occult
level: 2
school: illusion
type: utility
traditions: [arcane, occult]
deities: Nethys
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
range: touch
target: 1 creature or object
source: "Pathfinder Core Rulebook"
duration: unlimited
traits:
  - common
  - auditory
  - visual
  - illusion
components:
  - somatic
  - verbal
description: >
  You specify a trigger and a message up to 25 words long. When the specified trigger occurs within 30 feet of the target, an illusory mouth appears on the target and speaks the message, and the magic mouth spell ends.
---
# `=this.name`
==auditory== | ==visual== | ==illusion==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Deities** `=this.deities`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Targets** `=this.target`
**Duration** `=this.duration`

***
`=this.description`