---
name: Agonizing Despair
alias: Agonizing Despair
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_3
  - imported/pf2e/school/enchantment
  - imported/pf2e/spelltype/save
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/divine
  - imported/pf2e/tradition/occult
level: 3
school: enchantment
type: save
traditions: [arcane, divine, occult]
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
range: 60 feet
target: 1 creature
source: "Pathfinder Advanced Player's Guide"
save: will
basic: false
traits:
  - common
  - emotion
  - fear
  - mental
  - enchantment
components:
  - somatic
  - verbal
description: >
  Your target's mind tumbles down a deep well of dread, dwelling so intently on deep-seated fears that it's painful. The target takes 4d6 mental damage with a Will saving throw.

  &NewLine;**Critical Success** The target is unaffected.
  &NewLine;**Success** The target takes half damage and becomes [[Frightened]] 1.
  &NewLine;**Failure** The target takes full damage and becomes [[Frightened]] 2.
  &NewLine;**Critical Failure** The target takes double damage and becomes [[Frightened]] 3.

  &NewLine;**Heightened (+1)** Increase the damage by 2d6 mental.
---
# `=this.name`
==emotion== | ==fear== | ==mental== | ==enchantment==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Targets** `=this.target`
**Saving Throw** `=this.save`

***
`=this.description`