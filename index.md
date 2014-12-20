---
title       : Historical Snow Fall in Chicago US
subtitle    : Developing Data Product Project
author      : Helen Huang
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [bootstrap, interactive]            # {mathjax, quiz, bootstrap}
ext_widgets : {rCharts: [libraries/morris]}
mode        : selfcontained # {standalone, draft, selfcontained}


--- # Introduction and objectives

## Executive summary

As winter months in Chicago linger from Nov to April, snow is a serious weather event and can present challenges to the local residents and the authorities. 

This simple, **interactive** app provides an unique opportunity for the viewers to search for historical snow falls in Chicago winter from Nov, 1958 till Nov, 2014. 

Total monthly snow falls (inches) and concurrent average monthly air temperature (as max temp, min temp and average temp, F) are analyzed . 

Searchable information are displayed as 'Snow Fall' graph, 'Air Temp' graph and also summarized in table output format under 'Data' tab. 

(Data source: National Oceanic and Atmospheric Administration, NOAA, HTTP://WWW.nova.gov).

--- #shiny app

## Preview of 'Historical Chicago Snow Fall' app


![myapp](./assets/img/snapshot1.png)


**This is the link to the shiny app: https://helen.shinyapps.io/ChicagoSnow/**



--- #snow plot

## Total Monthly Snow Fall in Chicago (1958-present)

Search the **interactive** plots by selecting year/month in the sidebar or hovering the mouse cursor over the graph.

<iframe src=' assets/fig/s1-1.html ' scrolling='no' frameBorder='0' seamless class='rChart morris ' id=iframe- chartac5218dba76 ></iframe> <style>iframe.rChart{ width: 100%; height: 400px;}</style>

--- #temp plot and conclusion

## Average Monthly Temp in Chicago (1958-present)

<iframe src=' assets/fig/s2-1.html ' scrolling='no' frameBorder='0' seamless class='rChart morris ' id=iframe- chartac575b924cb ></iframe> <style>iframe.rChart{ width: 100%; height: 400px;}</style>

The matching snow fall and air temperature information are also available in table format under 'Data' tab. **The app link is: https://helen.shinyapps.io/ChicagoSnow/.**


