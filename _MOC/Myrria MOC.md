# Myrria MOC
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
table aka as "AKA", plane as "Plane", capital as "Capital"
FROM #location/nation 
```
## Items
### Generic Items
```dataview
table aka as "AKA", type as "Type", rarity as "Rarity"
FROM #item AND !#trait/rarity/unique
```
### Unique Items
```dataview
table aka as "AKA", type as "Type", fate as "Fate"
FROM #item AND #trait/rarity/unique 
```
## People
### Characters
```dataview
table aka as "AKA", pronouns as "Pronouns", type as "Type"
from #character
```
### Organizations
```dataview
table aka as "AKA", type as "Type"
from #organization 
```
### Deities
```dataview
table title as "Title", aka as "AKA", type as "Type", province as "Province"
FROM #deity
```

## Fundamentals
```dataview
list
FROM "myrria/fundamentals"
```
