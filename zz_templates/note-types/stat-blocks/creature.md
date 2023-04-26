---
aliases: "Name"
tags: 
- custom
- level/X
- trait/creature/type/
statblock: inline
name: "Name"
level: X
---

```statblock
layout: Path2eBlock
statblock: true
source: "CUSTOM"
name: "Name"
level: "Creature X"
rare_0X: rarity
alignment: "N"
size: "Size"
trait_01: "Trait"
trait_02: "Trait"
trait_03: "Trait"
trait_04: "Trait"
trait_05: "Trait"
trait_06: "Trait"
trait_07: "Trait"
modifier: X
perception:
  - name: "Perception"
    desc: "Perception +X; __darkvision__;"
skills:
  - name: "Skills"
    desc: "__Skill Name__: +X (1d20+X);"
abilityMods: [X, X, X, X, X, X]

abilities_mid:
  - name: "Ability Name"
    desc: "⬲ __Frequency__ text __Trigger__ text __Effect__  text"
abilities_bot:
  - name: "Ability Name"
    desc: "⬺ __Frequency__ text __Trigger__ text __Effect__  text"

speed: X feet, special X feet

ac: X
armorclass:
  - name: AC
    desc: "X; __Fort__: +X (1d20+X); __Ref__: +X (1d20+X); __Will__: +X (1d20+X);"
hp: X
health:
  - name: HP
    desc: "X;  __Immunities__ immunity name; __Weaknesses__ weakness name X; __Resistances__ resistance name X"

attacks:
  - name: Melee
    desc: "⬻ attack name +X (trait wikilink); __Damage__ XdY+Z (XdY+Z) damage type."

sourcebook: "_Custom_"
```

```encounter-table
name: Name
creatures:
  - 1: Name
```