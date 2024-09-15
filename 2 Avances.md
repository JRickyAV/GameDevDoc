---
cssclasses:
  - table-wide
tags:
  - Info
---
# Ticket ejemplo

# [[8 Objetivos de Versiones]]

# Singularity Alpha-1.0

```dataview
table
	progressBar AS "Progreso",	
	ticket AS "NombreTicket",
	description AS "Descripcion",
	assigned AS "Encargado"
	
	where progressBar != Null
	where version = "Alpha-1.0"
	where ticket != Null
	where description != Null
	sort ticket
```

