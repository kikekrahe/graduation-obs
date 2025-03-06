
```dataview
table without id
	file.link as "note",
	dateformat(file.cday, "dd-MM-yyyy") as "created"
from "1 - Sources" or "2 - Topics" or "4 - Main Notes" or "5 - Other"
sort file.cday desc
```


