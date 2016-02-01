---
title       : European Currency Conversion
subtitle    : Developing Data Products Course Presentation
author      : Mo Chen
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [shiny,mathjax]   # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
output: html_document
---

## Introduction

This shiny project is designed for online European currency conversion.
  
There are 11 European currencies:  
-Austrian Schilling ATS  
-Belgian Franc BEF  
-German Mark DEM  
-Spanish Peseta ESP   
-Finnish Markka FIM  
-French Franc FRF  
-Irish Punt IEP  
-Italian Lira ITL   
-Luxembourg Franc LUF   
-Dutch Guilder NLG  
-Portuguese Escudo PTE   
-Euro  
  
These conversion rates were fixed by the European Union on December 31, 1998.

--- 

## The dataset


```r
library(datasets)
data(euro)
```

Here use rCharts to plot the data. The value refers to the value of 1 euro in that currency.  

<iframe src=' assets/fig/unnamed-chunk-2-1.html ' scrolling='no' frameBorder='0' seamless class='rChart polycharts ' id=iframe- chart299281492bc ></iframe> <style>iframe.rChart{ width: 100%; height: 400px;}</style>

--- 

## The little math in currency conversion from A to B
1 currency A is equivalent to $$1\times \frac{Value(B)}{Value(A)}$$ of currency B.

---

## The shiny app 
Try the shiny app for European currency conversion

https://mollihua.shinyapps.io/project_DevelopingDataProducts/

Please email Mo Chen (mochenserey@gmail.com) for any questions.Thank you.


