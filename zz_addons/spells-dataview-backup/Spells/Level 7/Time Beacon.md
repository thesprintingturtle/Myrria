---
name: Time Beacon
alias: Time Beacon
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_7
  - imported/pf2e/school/divination
  - imported/pf2e/spelltype/utility
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/occult
level: 7
school: divination
type: utility
traditions: [arcane, occult]
deities: Shyka, Yog-Sothoth
time: 1 action
pf2etime: "*⬻{ .Pathfinder }*"
source: "Pathfinder Lost Omens: Gods & Magic"
duration: until the end of your turn
traits:
  - common
  - divination
components:
  - material
description: >
  You create a beacon in time, intending to return to it if things go wrong. You can cast time beacon on only your turn. Keep careful track of everything that happens this turn after you cast time beacon. At the end of your turn, you can choose to rewind time back to just after you cast time beacon, removing all effects of your turn since then. Curses, traps, and other harmful effects that happen during your turn might prevent you from returning to the beacon if they are powerful enough. If you suffered any harmful effects during your turn after casting time beacon, to return to your beacon, time beacon attempts a counteract check against each such effect. If it fails at any of these checks, you can't return. After returning to the time beacon, the spell ends.
---
# `=this.name`
==divination==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Deities** `=this.deities`
**Cast** `=this.time` | `=this.components`
**Duration** `=this.duration`

***
`=this.description`