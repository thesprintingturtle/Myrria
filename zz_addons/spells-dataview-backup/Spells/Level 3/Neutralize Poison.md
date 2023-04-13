---
name: Neutralize Poison
alias: Neutralize Poison
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_3
  - imported/pf2e/school/necromancy
  - imported/pf2e/spelltype/heal
  - imported/pf2e/tradition/divine
  - imported/pf2e/tradition/primal
level: 3
school: necromancy
type: heal
traditions: [divine, primal]
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
  You pour healing magic through the target in an attempt to cure one poison afflicting it. Attempt a counteract check against the poison.
---
# `=this.name`
==healing== | ==necromancy==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Targets** `=this.target`

***
`=this.description`