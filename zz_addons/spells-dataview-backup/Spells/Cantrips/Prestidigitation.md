---
name: Prestidigitation
alias: Prestidigitation
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
spelllist: elemental
time: 2 actions
pf2etime: "*⬺{ .Pathfinder }*"
range: 10 feet
target: 1 object (cook, lift, or tidy only)
source: "Pathfinder Core Rulebook"
duration: sustained
traits:
  - common
  - cantrip
  - evocation
components:
  - somatic
  - verbal
description: >
  The simplest magic does your bidding. You can perform simple magical effects for as long as you Sustain the Spell. Each time you Sustain the Spell, you can choose one of four options.

  Cook Cool, warm, or flavor 1 pound of nonliving material.
  Lift Slowly lift an unattended object of light Bulk or less 1 foot off the ground.
  Make Create a temporary object of negligible Bulk, made of congealed magical substance. The object looks crude and artificial and is extremely fragile-it can't be used as a tool, weapon, or spell component.
  Tidy Color, clean, or soil an object of light Bulk or less. You can affect an object of 1 Bulk with 10 rounds of concentration, and a larger object a 1 minute per Bulk.

  Prestidigitation can't deal damage or cause adverse conditions. Any actual change to an object (beyond what is noted above) persists only as long as you Sustain the Spell.
---
# `=this.name`
==cantrip== | ==evocation==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Spell List**: `=this.spelllist`
**Cast** `=this.time` | `=this.components`
**Range** `=this.range`; **Targets** `=this.target`
**Duration** `=this.duration`

***
`=this.description`