---
title: "Assignment9"
output: html_document
---

Summarize three columns
```{r}
summary(Dessert)
```
visually represents the data in some way
```{r}
library(ggplot2)
ggplot(Dessert, aes(rate, quantity, fill = dessert)) + geom_point() + theme_classic()
```

