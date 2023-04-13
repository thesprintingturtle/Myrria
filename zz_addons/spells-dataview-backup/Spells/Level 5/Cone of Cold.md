---
name: Cone of Cold
alias: Cone of Cold
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_5
  - imported/pf2e/school/evocation
  - imported/pf2e/spelltype/save
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/primal
level: 5
school: evocation
type: save
traditions: [arcane, primal]
deities: Alglenweis, Kostchtchie
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
area: 60-foot cone
source: "Pathfinder Core Rulebook"
save: reflex
basic: true
traits:
  - common
  - cold
  - evocation
components:
  - somatic
  - verbal
description: >
  Icy cold rushes forth from your hands. You deal 12d6 cold damage to creatures in the area.

  &NewLine;**Heightened (+1)** The damage increases by 2d6.
---
# `=this.name`
==cold== | ==evocation==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Deities** `=this.deities`
**Cast** `=this.time` | `=this.components`
**Area** `=this.area`
**Basic Saving Throw** `=this.save`

***
`=this.description`