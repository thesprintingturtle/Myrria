---
name: Life Pact
alias: Life Pact
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_3
  - imported/pf2e/school/necromancy
  - imported/pf2e/spelltype/heal
  - imported/pf2e/tradition/divine
  - imported/pf2e/tradition/occult
  - imported/pf2e/tradition/primal
level: 3
school: necromancy
type: heal
traditions: [divine, occult, primal]
time: 1 minute
pf2etime: ""
range: touch
target: up to 6 willing creatures
source: "Pathfinder Lost Omens: Knights of Lastwall"
access: Knights of Lastwall have access to this spell
duration: 10 minutes
traits:
  - uncommon
  - healing
  - necromancy
components:
  - material
  - somatic
  - verbal
description: >
  Using your life force or spirit as a conduit, you bind the targets in a mystical pact. If one of the targets is about to take damage that would reduce it to 0 Hit Points, all other targets immediately lose 3 Hit Points and the triggering target regains a number of Hit Points equal to the Hit Points lost this way, just before taking the damage. If this healing is enough that the triggering target is no longer reduced to 0 Hit Points, they remain conscious. Once the triggering target has regained Hit Points from the other targets, the spell ends.

  &NewLine;**Heightened (+1)** Increase the number of Hit Points lost by 1 for each target other than the one reduced to 0 Hit Points. The target reduced to 0 Hit Points regains that many additional Hit Points.
---
# `=this.name`
==uncommon== | ==healing== | ==necromancy==

*Source* `=this.source`
**Access** `=this.access`
**Traditions** `=this.traditions`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Targets** `=this.target`
**Duration** `=this.duration`

***
`=this.description`