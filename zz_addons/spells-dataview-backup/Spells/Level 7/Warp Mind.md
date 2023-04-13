---
name: Warp Mind
alias: Warp Mind
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_7
  - imported/pf2e/school/enchantment
  - imported/pf2e/spelltype/save
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/occult
level: 7
school: enchantment
type: save
traditions: [arcane, occult]
deities: Conqueror Worm, Nethys, Xhamen-Dor
bloodline: aberrant, hag
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
range: 120 feet
target: 1 creature
source: "Pathfinder Core Rulebook"
save: will
basic: false
traits:
  - common
  - emotion
  - incapacitation
  - mental
  - enchantment
components:
  - somatic
  - verbal
description: >
  You scramble a creature's mental faculties and sensory input. The target must attempt a Will saving throw. Regardless of the result of that save, the target is then temporarily immune for 10 minutes. Warp mind's effects happen instantly, so dispel magic and other effects that counteract spells can't counteract them. However, alter reality, miracle, primal phenomenon, restoration, or wish can still counteract the effects.

  &NewLine;**Critical Success** The target is unaffected.
  &NewLine;**Success** The target spends the first action on its next turn with the [[Confused]] condition.
  &NewLine;**Failure** The target is Confused for 1 minute.
  &NewLine;**Critical Failure** The target is Confused permanently.
---
# `=this.name`
==emotion== | ==incapacitation== | ==mental== | ==enchantment==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Deities** `=this.deities`
**Bloodline** `=this.bloodline`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Targets** `=this.target`
**Saving Throw** `=this.save`

***
`=this.description`