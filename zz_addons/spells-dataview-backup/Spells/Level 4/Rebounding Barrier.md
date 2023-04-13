---
name: Rebounding Barrier
alias: Rebounding Barrier
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_4
  - imported/pf2e/school/abjuration
  - imported/pf2e/spelltype/utility
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/occult
level: 4
school: abjuration
type: utility
traditions: [arcane, occult]
time: reaction
pf2etime: ""
trigger: You are hit by a physical Strike
source: "Pathfinder Lost Omens: Legends"
traits:
  - rare
  - abjuration
components:
  - verbal
description: >
  You swiftly raise a reflective barrier, reducing physical damage and rebounding it onto your attacker. You gain resistance 10 against one physical damage type the triggering attack deals. Your attacker takes 5 damage of the same type.

  &NewLine;**Heightened (+1)** The resistance increases by 2. Damage dealt to your attacker increases by 1.
---
# `=this.name`
==rare== | ==abjuration==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Cast** `=this.time` | `=this.components`

***
`=this.description`