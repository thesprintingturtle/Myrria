---
name: Magic Aura
alias: Magic Aura
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_1
  - imported/pf2e/school/illusion
  - imported/pf2e/spelltype/utility
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/occult
level: 1
school: illusion
type: utility
traditions: [arcane, occult]
time: 1 minute
pf2etime: ""
range: touch
target: 1 object of 3 bulk or less
source: "Pathfinder Core Rulebook"
duration: until the next time you make your daily preparations
traits:
  - uncommon
  - illusion
components:
  - material
  - somatic
  - verbal
description: >
  You alter the appearance of an item's magic aura. You can choose to have the target's aura appear as that of common magic item of twice magic aura's level or lower, or to have it register as being under the effects of a spell of your choice of magic aura's level or lower. If the target is magical, you can instead choose to have it appear as entirely non-magical. A caster using [[Detect Magic]] or [[Read Aura]] of an equal or higher spell level can attempt to disbelieve the illusion from magic aura. Magic aura doesn't mask the aura of spells that are 9th level or higher or of items that are 19th level or higher.

  &NewLine;**Heightened (3rd)** You can target a creature instead of an object. When you do, you can either conceal the auras of all magic items it has or have that creature's aura appear as if it were under the effect of a spell you know.
---
# `=this.name`
==uncommon== | ==illusion==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Targets** `=this.target`
**Duration** `=this.duration`

***
`=this.description`