---
name: Summoner's Precaution
alias: Summoner's Precaution
tags:
  - imported/pf2e/spell
  - imported/pf2e/spell/level_2
  - imported/pf2e/school/necromancy
  - imported/pf2e/spelltype/utility
  - imported/pf2e/tradition/arcane
  - imported/pf2e/tradition/divine
  - imported/pf2e/tradition/occult
  - imported/pf2e/tradition/primal
level: 2
school: necromancy
type: utility
traditions: [arcane, divine, occult, primal]
time: 10 minutes
pf2etime: ""
requirements: You have an eidolon
source: "Pathfinder Secrets of Magic"
duration: until your next daily preparations.
traits:
  - common
  - contingency
  - necromancy
components:
  - material
  - somatic
  - verbal
description: >
  You create a buffer in the link between yourself and your eidolon in order to prevent you from falling alongside your bonded ally. You gain the Sever Conduit reaction; after using it, the spell ends.

  **Sever Conduit | reaction | [[Concentrate]] | Trigger** Your eidolon takes damage that would bring you to 0 Hit Points and comes from an effect other than a [[Death]] effect; **Effect** You quickly shut the buffer in your link with your eidolon, causing your bonded ally to wink out 
---
# `=this.name`
==contingency== | ==necromancy==

*Source* `=this.source`
**Traditions** `=this.traditions`
**Cast** `=this.time` | `=this.components`; **Requirements** `=this.requirements`
**Duration** `=this.duration`

***
`=this.description`