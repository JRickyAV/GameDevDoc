---
tags:
  - Info
---
# Archivos no utilizados
```dataview
table
	FROM !#Info 
	where !contains(file.path,"Tickets")
	where progressBar = Null
```

# Tickets sin versiones 
```dataview
table
	where contains(file.path,"Tickets")
	where version = Null
```

# Tickets sin asignar
```dataview
table
	where contains(file.path,"Tickets")
	where assigned = Null
```

# Tickets sin progreso
```dataview
table
	where contains(file.path,"Tickets")
	where progressBar = Null
```

# Tickets sin nombre del ticket
```dataview
table
	where contains(file.path,"Tickets")
	where ticket = Null
```

