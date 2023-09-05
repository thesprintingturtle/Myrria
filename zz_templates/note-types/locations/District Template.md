---
aliases: 
---
**City/Superdistrict Link**
# <% tp.file.title %> *District (level:: X)*
#location/district  
Brief Description

- **Full Name**:: 
- **AKA**:: 
- **Government Structure**:: 
- **Head of Government**:: 

- **Settlement**:: 
- **Superdistrict**:: 
- **Subdistricts**
	```dataview
	table level as Level, Population as Population, AKA as AKA
	FROM #location/district 
	WHERE contains(superdistrict, "<% tp.file.title %>")
	```
- **Points of Interest**
	```dataview
	table Type as Type, level as Level, AKA as AKA
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