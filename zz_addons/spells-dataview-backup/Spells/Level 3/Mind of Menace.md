---
name: Mind of Menace
alias: Mind of Menace
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_3
  - imported/pf2e/school/enchantment
  - imported/pf2e/spelltype/utility
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/divine
  - imported/pf2e/tradition/occult
  - imported/pf2e/tradition/primal
level: 3
school: enchantment
type: utility
traditions: [arcane, divine, occult, primal]
lesson: lesson of favors
time: 10 minutes
pf2etime: ""
source: "Pathfinder Secrets of Magic"
duration: 24 hours
traits:
  - common
  - contingency
  - emotion
  - fear
  - mental
  - enchantment
components:
  - material
  - somatic
  - verbal
description: >
  This spell wards against those who attempt to subvert your mind and turns mental magic back on them. When the spell is complete, you gain the Fight with Fear reaction; once you use the reaction, the spell ends.

  **Fight with Fear | reaction | [[Concentrate]], [[Emotion]], [[Enchantment]], [[Fear]], [[Mental]] | Trigger** A creature that you can see uses a mental effect against you; **Effect** The triggering creature must attempt a Will save, which has the following effects.
---
# `=this.name`
==contingency== | ==emotion== | ==fear== | ==mental== | ==enchantment==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Lesson**: `=this.lesson`
**Cast** `=this.time` | `=this.components`
**Duration** `=this.duration`

***
`=this.description`