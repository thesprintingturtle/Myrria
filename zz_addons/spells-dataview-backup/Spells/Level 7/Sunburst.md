---
name: Sunburst
alias: Sunburst
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_7
  - imported/pf2e/school/evocation
  - imported/pf2e/spelltype/save
  - imported/pf2e/tradition/divine
  - imported/pf2e/tradition/primal
level: 7
school: evocation
type: save
traditions: [divine, primal]
spelllist: elemental
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
range: 500 feet
area: 60-foot burst
source: "Pathfinder Core Rulebook"
save: reflex
basic: false
traits:
  - common
  - fire
  - light
  - positive
  - evocation
components:
  - somatic
  - verbal
description: >
  A powerful globe of searing sunlight explodes in the area, dealing 8d10 fire damage to all creatures in the area, plus 8d10 additional positive damage to undead creatures. Each creature and object in the area must attempt a Reflex save. If the globe overlaps with an area of magical darkness, sunburst attempts to counteract the darkness effect.

  &NewLine;**Critical Success** The creature or object is unaffected.
  &NewLine;**Success** The creature takes half damage.
  &NewLine;**Failure** The creature takes full damage.
  &NewLine;**Critical Failure** The creature takes full damage. If it's a creature, it becomes [[Blinded]] permanently.

  &NewLine;**Heightened (+1)** The fire damage increases by 1d10, and the positive damage against undead increases by 1d10.
---
# `=this.name`
==fire== | ==light== | ==positive== | ==evocation==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Spell List**: `=this.spelllist`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Area** `=this.area`
**Saving Throw** `=this.save`

***
`=this.description`