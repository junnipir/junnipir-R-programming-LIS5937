---
title: "Comparing Amazon Product’s BSR and Category Rank to Number of Sales Per Day"
author: "Heather Ward"
date: "4/10/2022"
output: "html_document"

---

```{r setup, include=FALSE}
ggplot2(echo=TRUE)
```

#data that will be used for the final project. This may be subject to change, but here is where data will be loaded and briefly analyzed.
```{r}
data(amazondata)
str(amazondata)
summary(amazondata)
plot(amazondata)
```


#figures that will help in analyses. 
#
``` {r}
hist($amazondata$salesperday)
boxplot($amazondata$categoryrank)
```



#The End




