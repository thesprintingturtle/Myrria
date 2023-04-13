---
name: Remove Paralysis
alias: Remove Paralysis
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_2
  - imported/pf2e/school/necromancy
  - imported/pf2e/spelltype/heal
  - imported/pf2e/tradition/divine
  - imported/pf2e/tradition/occult
  - imported/pf2e/tradition/primal
level: 2
school: necromancy
type: heal
traditions: [divine, occult, primal]
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
range: touch
target: 1 creature
source: "Pathfinder Core Rulebook"
traits:
  - common
  - healing
  - necromancy
components:
  - somatic
  - verbal
description: >
  A surge of energy frees a [[Paralyzed]] creature. You can attempt to counteract a single effect imposing the Paralyzed condition on the target. This does not cure someone who is Paralyzed from some natural state or effect, such as paralysis caused by non-magical wounds or toxins.

  &NewLine;**Heightened (6th)** The spell's range increases to 30 feet, and you can target up to 10 creatures.
---
# `=this.name`
==healing== | ==necromancy==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Targets** `=this.target`

***
`=this.description`