---
name: Forbidding Ward
alias: Forbidding Ward
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/cantrip_1
  - imported/pf2e/school/abjuration
  - imported/pf2e/spelltype/utility
  - imported/pf2e/tradition/divine
  - imported/pf2e/tradition/occult
level: 1
school: abjuration
type: utility
traditions: [divine, occult]
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
range: 30 feet
target: 1 ally and 1 enemy
source: "Pathfinder Core Rulebook"
duration: sustained up to 1 minute
traits:
  - common
  - cantrip
  - abjuration
components:
  - somatic
  - verbal
description: >
  You ward an ally against the attacks and hostile spells from the target enemy. The target ally gains a +1 status bonus to Armor Class and saving throws against the target enemy's attacks, spells, and other effects.
  &NewLine;**Heightened (6th)** The status bonus increases to +2.
---
# `=this.name`
==cantrip== | ==abjuration==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Targets** `=this.target`
**Duration** `=this.duration`

***
`=this.description`