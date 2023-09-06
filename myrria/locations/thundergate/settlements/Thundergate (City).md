---
aliases: 
---
**Nation Link**
# Thundergate (City) *Settlement (level:: 12)*
#location/settlement/city 
Brief Description

- **Full Name**:: 
- **AKA**:: 
- **Government Structure**:: 
- **Head of Government**:: 

- **Nation**:: 
- **Region**:: 
- **Districts**
	```dataview
	table level as Level, Population as Population, AKA as AKA
	FROM #location/district 
	WHERE contains(settlement, "Thundergate (City)")
	```
- **Points of Interest**
	```dataview
	table Type as Type, level as Level, AKA as AKA
	FROM #location/poi 
	WHERE contains(location, "Thundergate (City)")
	```
- **Population**:: 
- **Ancestries**:: 
- **Languages**:: 
- **Religions**:: 

## Description

## Society
### Demographics

### Politics

### Military

### Laws

### Religion

## History