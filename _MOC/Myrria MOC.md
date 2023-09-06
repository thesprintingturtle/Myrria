# Myrria MOC
#exclude
Map of content for all things Myrria
## Ancestries/Heritages
### Ancestries
```dataview
table type as "Type", heritages as "Heritages"
from #ancestry 
```
### Heritages
```dataview
table
FROM #heritage
```
## Ecology
### Fauna
```dataview
table
FROM #fauna
```
### Flora
```dataview
table
FROM #flora
```

## Locations
### Geography
```dataview
table
FROM #geography
```
### Nations
```dataview
table plane as Plane, capital as Capital, aka as AKA
FROM #location/nation 
```
## Items
### Generic Items
```dataview
table type as "Type", rarity as "Rarity", aka as AKA
FROM #item AND !#trait/rarity/unique
```
### Unique Items
```dataview
table type as "Type", fate as "Fate", aka as AKA
FROM #item AND #trait/rarity/unique 
```
## People
### Characters
```dataview
table pronouns as "Pronouns", type as "Type", aka as AKA
from #character
```
### Organizations
```dataview
table type as "Type", member-count as "Member Count", aka as AKA
from #organization 
```
### Deities
```dataview
table title as "Title", type as "Type", province as "Province", aka as AKA
FROM #deity
```

## Fundamentals
```dataview
list
FROM "myrria/fundamentals"
```
