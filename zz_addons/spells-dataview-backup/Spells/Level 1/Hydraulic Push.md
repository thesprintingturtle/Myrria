---
name: Hydraulic Push
alias: Hydraulic Push
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_1
  - imported/pf2e/school/evocation
  - imported/pf2e/spelltype/attack
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/primal
level: 1
school: evocation
type: attack
traditions: [arcane, primal]
deities: Besmara, Dagon, Hanspur, Lysianassa, Ragadahn, Sobek
spelllist: elemental
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
range: 60 feet
target: 1 creature or unattended object
source: "Pathfinder Core Rulebook"
traits:
  - common
  - attack
  - water
  - evocation
components:
  - somatic
  - verbal
description: >
  You call forth a powerful blast of pressurized water that bludgeons the target and knocks it back. Make a ranged spell attack roll.

  &NewLine;**Critical Success** The target takes 6d6 bludgeoning damage and is knocked back 10 feet.
  &NewLine;**Success** The target takes 3d6 bludgeoning damage and is knocked back 5 feet.

  &NewLine;**Heightened (+1)** The damage increases by 2d6.
---
# `=this.name`
==attack== | ==water== | ==evocation==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Deities** `=this.deities`
**Spell List**: `=this.spelllist`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Targets** `=this.target`

***
`=this.description`