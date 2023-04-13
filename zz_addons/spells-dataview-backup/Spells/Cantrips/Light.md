---
name: Light
alias: Light
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/cantrip_1
  - imported/pf2e/school/evocation
  - imported/pf2e/spelltype/utility
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/divine
  - imported/pf2e/tradition/occult
  - imported/pf2e/tradition/primal
level: 1
school: evocation
type: utility
traditions: [arcane, divine, occult, primal]
bloodline: angelic
spelllist: elemental
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
range: touch
target: 1 object of 1 Bulk or less, either unattended or possessed by you or a willing ally
source: "Pathfinder Core Rulebook"
duration: until the next time you make your daily preparations
traits:
  - common
  - light
  - cantrip
  - evocation
components:
  - somatic
  - verbal
description: >
  The object glows, casting bright light in a 20-foot radius (and dim light for the next 20 feet) like a torch. If you cast this spell again on a second object, the light spell on the first object ends.

  &NewLine;**Heightened (4th)** The object sheds bright light in a 60-foot radius (and dim light for the next 60 feet).
---
# `=this.name`
==light== | ==cantrip== | ==evocation==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Bloodline** `=this.bloodline`
**Spell List**: `=this.spelllist`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Targets** `=this.target`
**Duration** `=this.duration`

***
`=this.description`