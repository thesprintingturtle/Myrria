---
name: Final Sacrifice
alias: Final Sacrifice
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_2
  - imported/pf2e/school/evocation
  - imported/pf2e/spelltype/save
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/divine
  - imported/pf2e/tradition/occult
  - imported/pf2e/tradition/primal
level: 2
school: evocation
type: save
traditions: [arcane, divine, occult, primal]
spelllist: elemental
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
range: 120 feet
target: 1 creature with the minion trait that you summoned or permanently control
source: "Pathfinder Advanced Player's Guide"
save: reflex
basic: true
traits:
  - common
  - fire
  - evocation
components:
  - somatic
  - verbal
description: >
  You channel disruptive energies through the bond between you and your minion, causing it to violently explode. The target is immediately slain, and the explosion deals 6d6 fire damage to creatures within 20 feet of it (basic Reflex save). If the target has the cold or water trait, the spell instead deals cold damage and gains the cold trait in place of the fire trait. If used on a creature that isn't mindless, this spell has the evil trait. Attempting to cast this spell targeting a creature that you temporarily seized control of, such as an undead commanded by Command Undead, automatically fails and breaks the controlling effect.

  &NewLine;**Heightened (+1)** The damage increases by 2d6 fire damage.
---
# `=this.name`
==fire== | ==evocation==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Spell List**: `=this.spelllist`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Targets** `=this.target`
**Basic Saving Throw** `=this.save`

***
`=this.description`