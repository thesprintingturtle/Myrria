---
name: Dull Ambition
alias: Dull Ambition
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_4
  - imported/pf2e/school/enchantment
  - imported/pf2e/spelltype/save
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/divine
  - imported/pf2e/tradition/occult
level: 4
school: enchantment
type: save
traditions: [arcane, divine, occult]
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
range: 120 feet
target: 1 creature
source: "Pathfinder Advanced Player's Guide"
duration: varies
save: will
basic: false
traits:
  - common
  - curse
  - mental
  - misfortune
  - enchantment
components:
  - somatic
  - verbal
description: >
  You curse the target to fail in all avenues of its life that require drive and ambition, as it inadvertently undermines its own goals at every turn. The effect is based on the target's Will save.

  &NewLine;**Critical Success** The target is unaffected.
  &NewLine;**Success** For 1 hour, the target rolls twice and uses the lower result on initiative rolls.
  &NewLine;**Failure** For 1 day, the target rolls twice and uses the lower result on initiative rolls and any check to determine the success of a downtime activity.
  &NewLine;**Critical Failure** As failure, but the duration is unlimited.
---
# `=this.name`
==curse== | ==mental== | ==misfortune== | ==enchantment==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Targets** `=this.target`
**Saving Throw** `=this.save`; **Duration** `=this.duration`

***
`=this.description`