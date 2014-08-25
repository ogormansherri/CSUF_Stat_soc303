---
title: "Instructions"
author: "Sherri Verdugo"
date: "August 24, 2014"
output:
  html_document:
    highlight: espresso
    theme: cosmo
    toc: yes
    toc_depth: 3
  pdf_document:
    highlight: espresso
    toc: yes
    toc_depth: 3
  word_document: default
---

To start the slide process:


```r
library(slidify)
library(rCharts)
author('slides1')

#to generate the slides:
slidify("index.RMD")
browseURL("index.html")

#to publish
publish(title = 'mytitle', 'index.html', host = 'rpubs')
```
