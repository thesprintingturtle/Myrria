---
name: Power Word Blind
alias: Power Word Blind
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_7
  - imported/pf2e/school/enchantment
  - imported/pf2e/spelltype/utility
  - imported/pf2e/tradition/arcane
level: 7
school: enchantment
type: utility
traditions: [arcane]
time: 1 action
pf2etime: "*⬻{ .Pathfinder }*"
range: 30 feet
target: 1 creature
source: "Pathfinder Core Rulebook"
duration: varies
traits:
  - uncommon
  - auditory
  - mental
  - enchantment
components:
  - verbal
description: >
  You utter an arcane word of power that can make the target [[Blinded]] upon hearing it. Once targeted, the target is then temporarily immune for 10 minutes. The effect of the spell depends on the target's level.

  &NewLine;**11th or Lower** The target is Blinded permanently.
  &NewLine;**12th-13th** The target is Blinded for 1d4 minutes.
  &NewLine;**14th or Higher** The target is [[Dazzled]] for 1 minute.

  &NewLine;**Heightened (+1)** The levels at which each outcome applies increase by 2.
---
# `=this.name`
==uncommon== | ==auditory== | ==mental== | ==enchantment==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Targets** `=this.target`
**Duration** `=this.duration`

***
`=this.description`