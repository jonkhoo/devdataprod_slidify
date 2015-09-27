---
title       : Developing Data Products Project 
subtitle    : Investigating DJIA from 1987 to 2015
author      : Khoo Hui Tiong
job         : Consultant
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Introduction

This application investigates the Dow Jones Industrial Average (DJIA) index value from 1985 Feb to 2015 Sep. We try to perform server calculation by predicting the index value for the future using forecasting.

--- .class #id 

## Application Controls

* The application requires the user to first select the period of trading. This can be done by selecting the dates from "Date Range". 

* Next the user can select whether to plot a line graph or a bar chart.

* There are 4 types of data available (High, Open, Low, Close). These are the different index value at each trading day.

* Finally, the user can select the number of days of prediction. The calculation is perform at the server end.

--- .class #id 

## Application 

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1-1.png) 

* [Link to Shiny App] (https://jonkhoo.shinyapps.io/devdataprod)

--- .class #id 

## References

* The application uses data from [Wall Street Journal](http://quotes.wsj.com/index/DJIA/historical-prices). 

* Github https://github.com/jonkhoo/devdataprod

* Shiny App https://jonkhoo.shinyapps.io/devdataprod

