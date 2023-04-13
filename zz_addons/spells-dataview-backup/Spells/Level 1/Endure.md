---
name: Endure
alias: Endure
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_1
  - imported/pf2e/school/enchantment
  - imported/pf2e/spelltype/heal
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/occult
level: 1
school: enchantment
type: heal
traditions: [arcane, occult]
deities: Arazni, Arqueros, Fandarra, Folgrit, Narakaas, Trudd
time: 1 action
pf2etime: "*⬻{ .Pathfinder }*"
range: touch
target: 1 creature
source: "Pathfinder Lost Omens: Gods & Magic"
duration: 1 round
traits:
  - common
  - mental
  - enchantment
components:
  - somatic
description: >
  You invigorate the touched creature's mind and urge it to press on. You grant the touched creature 5 temporary Hit Points.

  &NewLine;**Heightened (+1)** Increase the temporary Hit Points by 5.
---
# `=this.name`
==mental== | ==enchantment==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Deities** `=this.deities`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Targets** `=this.target`
**Duration** `=this.duration`

***
`=this.description`