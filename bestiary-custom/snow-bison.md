---
aliases: "Snow Bison"
tags: 
- custom
- level/1
- trait/creature/type/animal
statblock: inline
name: "Snow Bison"
level: 1
---

```statblock
layout: Path2eBlock
statblock: true
source: "CUSTOM"
name: "Snow Bison"
level: "Creature 1"
alignment: "N"
size: "Large"
trait_01: "[Animal](../_rules/traits/animal.md)"
modifier: 5
perception:
  - name: "Perception"
    desc: "Perception +5"
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +6 (1d20+6); __Athletics__: +7 (1d20+7);"
abilityMods: [+4, +3, +4, -4, +2, -1]

abilities_mid:
  - name: "Cold Adaptation"
    desc: "The snow bison treats environmental cold effects as if they were one step less extreme and ignore the effect of reducing daily travel time."
  - name: "Buck"
    desc: "⬲ DC 16"

speed: 40 feet

ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__: +9 (1d20+9); __Ref__: +6 (1d20+6); __Will__: +5 (1d20+5);"
hp: 22
health:
  - name: HP
    desc: "22;  __Resistances__ cold 3"

attacks:
  - name: Melee
    desc: "⬻ horn +7; __Damage__ 1d6+4 (1d6+4) piercing"

sourcebook: "_Custom_"
```

```encounter-table
name: Snow Bison
creatures:
  - 1: Snow Bison
```