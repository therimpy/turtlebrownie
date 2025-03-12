# <u>**Current Commissions**</u>
```dataview
TABLE WITHOUT ID
	name AS Commission,
	client AS Client,
	type AS Type,
	size AS Size,
	colour AS Colour,
	contact AS Contact
FROM "Commissions"
GROUP BY status
SORT file.ctime ASC
```