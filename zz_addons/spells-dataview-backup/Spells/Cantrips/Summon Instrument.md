---
name: Summon Instrument
alias: Summon Instrument
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/cantrip_1
  - imported/pf2e/school/conjuration
  - imported/pf2e/spelltype/utility
  - imported/pf2e/tradition/divine
  - imported/pf2e/tradition/occult
level: 1
school: conjuration
type: utility
traditions: [divine, occult]
time: 3 actions
pf2etime: "*⬽{ .Pathfinder }*"
source: "Pathfinder Advanced Player's Guide"
duration: 1 hour
traits:
  - common
  - cantrip
  - conjuration
components:
  - material
  - somatic
  - verbal
description: >
  You materialize a Musical Instrument (Handheld) in your grasp. The instrument is typical for its type, but it plays only for you. The instrument vanishes when the spell ends. If you cast summon instrument again, any instrument you previously summoned disappears.

  &NewLine;**Heightened (5th)** The instrument is instead a Musical Instrument (Virtuoso handheld)
---
# `=this.name`
==cantrip== | ==conjuration==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Cast** `=this.time` | `=this.components`
**Duration** `=this.duration`

***
`=this.description`