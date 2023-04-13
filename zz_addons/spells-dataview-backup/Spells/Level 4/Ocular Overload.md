---
name: Ocular Overload
alias: Ocular Overload
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_4
  - imported/pf2e/school/illusion
  - imported/pf2e/spelltype/utility
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/occult
  - imported/pf2e/tradition/primal
level: 4
school: illusion
type: utility
traditions: [arcane, occult, primal]
time: 10 minutes
pf2etime: ""
source: "Pathfinder Secrets of Magic"
duration: 24 hours
traits:
  - common
  - contingency
  - incapacitation
  - visual
  - illusion
components:
  - material
  - somatic
  - verbal
description: >
  Just as a creature is about to attack you, you assault them with jarring illusions, completely surrounding their eyes with blinding flashes of motion and color. When the spell is complete, you gain the Overload Vision reaction; once you use the reaction, the spell ends.

  &NewLine;**Overload Vision | reaction | [[concentrate]]) | Trigger** A creature within 60 feet would make an attack roll against you; **Effects** The triggering creature must attempt a Fortitude save.
---
# `=this.name`
==contingency== | ==incapacitation== | ==visual== | ==illusion==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Cast** `=this.time` | `=this.components`
**Duration** `=this.duration`

***
`=this.description`