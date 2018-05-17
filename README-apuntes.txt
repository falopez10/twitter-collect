SQL
Database Browser for SQLite: sqlitebrowser.org
	Es mas complicado usar una base de datos en python.
	Más complicado que usar texto plano o diccionarios.
	Solo usar si es en verdad necesario.
	Casos en que es necesario:
		1) when your application needs to make small many random updates 
		within a large data set
		2) when your data is so large it cannot fit in a dictionary and 
		you need to look up information repeatedly
		3) when you have a long-running process that you want to be able
		to stop and restart and retain the data from one run to the next.