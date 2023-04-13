---
name: Haunting Hymn
alias: Haunting Hymn
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/cantrip_1
  - imported/pf2e/school/evocation
  - imported/pf2e/spelltype/save
  - imported/pf2e/tradition/divine
  - imported/pf2e/tradition/occult
level: 1
school: evocation
type: save
traditions: [divine, occult]
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
area: 15-foot cone
source: "Pathfinder Secrets of Magic"
save: fortitude
basic: true
traits:
  - common
  - auditory
  - cantrip
  - sonic
  - evocation
components:
  - somatic
  - verbal
description: >
  You echo a jarring hymn that only creatures in the area can hear. The hymn deals sonic damage equal to your spellcasting ability modifier, with a basic Fortitude save. If a target critically fails the save, it's also [[Deafened]] for 1 minute.

  &NewLine;**Heightened (+2)** The damage increases by 1d6.
---
# `=this.name`
==auditory== | ==cantrip== | ==sonic== | ==evocation==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Cast** `=this.time` | `=this.components`
**Area** `=this.area`
**Basic Saving Throw** `=this.save`

***
`=this.description`