---
name: Swarming Wasp Stings
alias: Swarming Wasp Stings
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_4
  - imported/pf2e/school/necromancy
  - imported/pf2e/spelltype/save
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/primal
level: 4
school: necromancy
type: save
traditions: [arcane, primal]
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
range: 30 feet
target: 10-foot burst
source: "Pathfinder #160: Assault on Hunting Lodge Seven"
save: fortitude
basic: false
traits:
  - uncommon
  - poison
  - necromancy
components:
  - somatic
  - verbal
description: >
  You manifest a swarm of disembodied wasp stingers that stab creatures in the area, possibly poisoning them. Creatures in the affected area take 1d6 piercing damage. Each creature that takes piercing damage must attempt a Fortitude save.

  &NewLine;**Critical Success** The target is unaffected.
  &NewLine;**Success** The target takes 2d6 poison damage.
  &NewLine;**Failure** The target is afflicted with Swarming Wasp Venom at stage 1.
  &NewLine;**Critical Failure** The target is afflicted with swarming wasp venom at stage 2.

  &NewLine;**Swarming Wasp Venom (poison) Level 7**
  &NewLine;Maximum Duration 6 rounds
  &NewLine;Stage 1 2d6 poison damage and [[Clumsy]] 1 (1 round)
  &NewLine;Stage 2 3d6 poison damage and [[Clumsy]] 2 (1 round)
---
# `=this.name`
==uncommon== | ==poison== | ==necromancy==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Targets** `=this.target`
**Saving Throw** `=this.save`

***
`=this.description`