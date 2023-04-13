---
name: Blazing Dive
alias: Blazing Dive
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_3
  - imported/pf2e/school/evocation
  - imported/pf2e/spelltype/save
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/primal
level: 3
school: evocation
type: save
traditions: [arcane, primal]
spelllist: elemental
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
area: 10-foot emanation
source: "Pathfinder Secrets of Magic"
save: reflex
basic: true
traits:
  - common
  - air
  - fire
  - evocation
components:
  - somatic
  - verbal
description: >
  Superheated air collects under you, buoying you high into the sky before you plummet back down in a fiery comet. You Fly 15 feet straight up into the air, then Fly in a straight line to an empty space of your choice on the ground within 60 feet. When you land, the blistering air blasts out from you, dealing 3d4 bludgeoning damage and 3d6 fire damage (basic Reflex save) to all creatures in a 10-foot emanation.

  &NewLine;**Heightened (+1)** The damage increases by 1d4 bludgeoning and 1d6 fire.
---
# `=this.name`
==air== | ==fire== | ==evocation==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Spell List**: `=this.spelllist`
**Cast** `=this.time` | `=this.components`
**Area** `=this.area`
**Basic Saving Throw** `=this.save`

***
`=this.description`