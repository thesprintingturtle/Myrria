---
aliases: 
---
**Nation Link**
# <% tp.file.title %> *Settlement (level:: X)*
#location/settlement 
Brief Description

- **Full Name**:: 
- **AKA**:: 
- **Government Structure**:: 
- **Head of Government**:: 

- **Nation**:: 
- **Region**:: 
- **Districts**
	```dataview
	table
	FROM #location/district 
	WHERE contains(settlement, "<% tp.file.title %>")
	```
- **Points of Interest**
	```dataview
	table
	FROM #location/poi 
	WHERE contains(location, "<% tp.file.title %>")
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