---
name: Blur
alias: Blur
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
deities: Black Butterfly
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
range: touch
target: 1 creature
source: "Pathfinder Core Rulebook"
duration: 1 minute
traits:
  - common
  - visual
  - illusion
components:
  - somatic
  - verbal
description: >
  The target's form appears blurry. It becomes [[Concealed]]. As the nature of this effect still leaves the target's location obvious, the target can't use this concealment to Hide or Sneak.
---
# `=this.name`
==visual== | ==illusion==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Deities** `=this.deities`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Targets** `=this.target`
**Duration** `=this.duration`

***
`=this.description`