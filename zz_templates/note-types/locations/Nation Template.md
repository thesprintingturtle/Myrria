---
aliases: 
---
**[Nations MOC](Myrria%20MOC#Nations)**
# <% tp.file.title %> *Nation*
#location/nation 
Brief Description

- **Full Name**:: 
- **AKA**:: 
- **Type**:: 

- **Government Structure**:: 
- **Head of Government**:: 
- **Military**:: 

- **Plane**:: 
- **Capital**::  

- **Ancestries**:: 
- **Languages**:: 
- **Religions**:: 

## Geography and Environment

## Society
#### Cities
```dataview
table level as Level, population as Population, aka as AKA
FROM #location/settlement/city 
WHERE contains(nation, this.file.name)
```
#### Towns
```dataview
table level as Level, population as Population, aka as AKA
FROM #location/settlement/town 
WHERE contains(nation, this.file.name)
```
### Demographics

### Politics

### Military

### Laws

### Religion

## History
