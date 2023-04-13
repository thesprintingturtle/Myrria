---
name: Prismatic Armor
alias: Prismatic Armor
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_7
  - imported/pf2e/school/abjuration
  - imported/pf2e/spelltype/utility
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/occult
level: 7
school: abjuration
type: utility
traditions: [arcane, occult]
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
range: touch
target: 1 willing creature
source: "Pathfinder Secrets of Magic"
duration: 1 minute
traits:
  - common
  - abjuration
components:
  - somatic
  - verbal
description: >
  You wrap the target in armor made of multicolored light. It functions as [[Chromatic Armor]] that is all colors (granting resistance 5 to acid, electricity, fire, force, mental, poison, and sonic). An attacker that critically fails on its saving throw against the spell is [[Blinded]] rather than [[Dazzled]].

  &NewLine;**Heightened (9th)** The resistances increase to 10 each.
---
# `=this.name`
==abjuration==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Targets** `=this.target`
**Duration** `=this.duration`

***
`=this.description`