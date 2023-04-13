---
name: Brand the Impenitent
alias: Brand the Impenitent
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_2
  - imported/pf2e/school/abjuration
  - imported/pf2e/spelltype/save
  - imported/pf2e/tradition/divine
level: 2
school: abjuration
type: save
traditions: [divine]
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
range: touch
target: 1 creature
source: "Pathfinder Lost Omens: Gods & Magic"
duration: varies
save: fortitude
basic: false
traits:
  - common
  - curse
  - abjuration
components:
  - somatic
  - verbal
description: >
  You brand the target with an ethereal copy of your deity's religious symbol. This brand can't be hidden, but it is visible only to followers of your faith, who see it as clearly as a lit torch. Followers of your faith ignore the target's [[Concealed]] condition, if any, and the target gains a -1 status penalty to AC against attacks by followers of your faith. If the target is a follower of your deity in good standing, the spell fails.

  &NewLine;**Critical Success** The target is unaffected.
  &NewLine;**Success** The spell lasts for 1 round.
  &NewLine;**Failure** The spell lasts for 1 minute.
  &NewLine;**Critical Failure** The spell has an unlimited duration.
---
# `=this.name`
==curse== | ==abjuration==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Targets** `=this.target`
**Saving Throw** `=this.save`; **Duration** `=this.duration`

***
`=this.description`