---
name: Resist Energy
alias: Resist Energy
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_2
  - imported/pf2e/school/abjuration
  - imported/pf2e/spelltype/utility
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/divine
  - imported/pf2e/tradition/occult
  - imported/pf2e/tradition/primal
level: 2
school: abjuration
type: utility
traditions: [arcane, divine, occult, primal]
bloodline: draconic, elemental, wyrmblessed
spelllist: elemental
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
range: touch
target: 1 creature
source: "Pathfinder Core Rulebook"
duration: 10 minutes
traits:
  - common
  - abjuration
components:
  - somatic
  - verbal
description: >
  A shield of elemental energy protects a creature against one type of energy damage. Choose acid, cold, electricity, fire, or sonic damage. The target and its gear gain resistance 5 against the damage type you chose.

  &NewLine;**Heightened (4th)** The resistance increases to 10, and you can target up to two creatures.
  &NewLine;**Heightened (7th)** The resistance increases to 15, and you can target up to five creatures.
---
# `=this.name`
==abjuration==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Bloodline** `=this.bloodline`
**Spell List**: `=this.spelllist`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Targets** `=this.target`
**Duration** `=this.duration`

***
`=this.description`