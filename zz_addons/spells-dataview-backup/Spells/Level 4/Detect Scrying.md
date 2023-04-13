---
name: Detect Scrying
alias: Detect Scrying
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_4
  - imported/pf2e/school/divination
  - imported/pf2e/spelltype/utility
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/occult
level: 4
school: divination
type: utility
traditions: [arcane, occult]
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
area: 30-foot emanation
source: "Pathfinder Core Rulebook"
duration: 1 hour
traits:
  - uncommon
  - detection
  - divination
components:
  - somatic
  - verbal
description: >
  By tapping into trace divinatory auras, you detect the presence of scrying effects in the area. If detect scrying is higher level than a scrying effect, you gain a glimpse of the scrying creature and learn its approximate distance and direction.

  &NewLine;**Heightened (6th)** The duration is until the next time you make your daily preparations.
---
# `=this.name`
==uncommon== | ==detection== | ==divination==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Cast** `=this.time` | `=this.components`
**Area** `=this.area`
**Duration** `=this.duration`

***
`=this.description`