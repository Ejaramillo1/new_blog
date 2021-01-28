---
title: test post
output:
  html_notebook:
    df_print: paged
    number_sections: yes
    theme: lumen
    toc: yes
  html_document:
    df_print: paged
    toc: yes
  pdf_document:
    toc: yes
author: yo
date: '2021-01-28'
slug: []
categories: []
tags: []
description: ''
featured: ''
featuredalt: ''
featuredpath: ''
linktitle: ''
type: post
---


# Set Knitr Options

```r
library(rmarkdown)
library(knitr)

opts_chunk$set(
  echo=TRUE,
  dpi=300,
  fig.width=5
  )
```

# Plot

```r
plot(cars)
```

<img src="index_files/figure-html/unnamed-chunk-1-1.png" width="1500" />
