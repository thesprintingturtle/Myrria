---
name: Darkvision
alias: Darkvision
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_2
  - imported/pf2e/school/divination
  - imported/pf2e/spelltype/utility
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/divine
  - imported/pf2e/tradition/occult
  - imported/pf2e/tradition/primal
level: 2
school: divination
type: utility
traditions: [arcane, divine, occult, primal]
spelllist: elemental
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
source: "Pathfinder Core Rulebook"
duration: 1 hour
traits:
  - common
  - divination
components:
  - somatic
  - verbal
description: >
  You grant yourself supernatural sight in areas of darkness. You gain Darkvision.

  &NewLine;**Heightened (3rd)** The spell's range is touch and it targets 1 willing creature.
  &NewLine;**Heightened (5th)** The spell's range is touch and it targets 1 willing creature. The duration is until the next time you make your daily preparations.
---
# `=this.name`
==divination==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Spell List**: `=this.spelllist`
**Cast** `=this.time` | `=this.components`
**Duration** `=this.duration`

***
`=this.description`