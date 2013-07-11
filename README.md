googleVis
=========

Personal copy of googleVis, including mods 

based on http://cran.r-project.org/src/contrib/googleVis_0.4.3.tar.gz

Allows for a 'formats' param to gvisTable, listing numberFormats per field summarised

Ex usage : 
``` R
library(googleVis)
data(Stock)

plot(gvisTable(Stock, formats = list(Value = "#,###")))
```

