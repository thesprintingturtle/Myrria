---
name: Sending
alias: Sending
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_5
  - imported/pf2e/school/divination
  - imported/pf2e/spelltype/utility
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/divine
  - imported/pf2e/tradition/occult
level: 5
school: divination
type: utility
traditions: [arcane, divine, occult]
time: 3 actions
pf2etime: "*⬽{ .Pathfinder }*"
range: planetary
target: 1 creature with whom you are familiar
source: "Pathfinder Core Rulebook"
traits:
  - common
  - mental
  - divination
components:
  - material
  - somatic
  - verbal
description: >
  You send the creature a mental message of 25 words or fewer, and it can respond immediately with its own message of 25 words or fewer.
---
# `=this.name`
==mental== | ==divination==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Targets** `=this.target`

***
`=this.description`