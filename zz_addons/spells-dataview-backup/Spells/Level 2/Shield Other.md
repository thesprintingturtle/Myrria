---
name: Shield Other
alias: Shield Other
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_2
  - imported/pf2e/school/necromancy
  - imported/pf2e/spelltype/utility
  - imported/pf2e/tradition/divine
level: 2
school: necromancy
type: utility
traditions: [divine]
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
range: 30 feet
target: 1 creature
source: "Pathfinder Core Rulebook"
duration: 10 minutes
traits:
  - common
  - necromancy
components:
  - somatic
  - verbal
description: >
  You forge a temporary link between the target's life essence and your own. The target takes half damage from all effects that deal Hit Point damage, and you take the remainder of the damage. When you take damage through this link, you don't apply any resistances, weaknesses, or other abilities you have to that damage; you simply take that amount of damage. The spell ends if the target is ever more than 30 feet away from you. If either you or the target is reduced to 0 Hit Points, any damage from this spell is resolved and then the spell ends.
---
# `=this.name`
==necromancy==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Targets** `=this.target`
**Duration** `=this.duration`

***
`=this.description`