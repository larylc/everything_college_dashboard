## Everything College Dashboard

## [Website Link](https://loganlary.shinyapps.io/shiny_college_app/)

## About

### Advantages over other college websites: 

+ While most college websites only allow you to compare colleges 1 at a time, users can use this dashboard to compare 2 colleges side by side. 
+ Users can look at a wide range of variables including: school stats, tuition, completion rate, debt, diversity, standardized scores, earnings after enrollment, and many more. 
+ This Dashboard allows users to adjust variables and observe changes over time. 

### R Packages Used:

```
library(tidyverse)
library(data.table)
library(lubridate)
library(reticulate)

library(gghighlight)
library(ggridges)
library(ggthemes)
library(extrafont)
library(ggtext)

library(knitr)
library(extrafont)
library(lattice)
library(gridExtra)
library(pryr)
library(highcharter)
library(gtExtras)
library(formattable)
library(shiny)
library(shinydashboard)
library(shinythemes)
library(shinyWidgets)
library(leaflet)
library(leaflet.extras)
library(htmltools)
library(magrittr)
library(plotly)
```

## Sources

+ You can find all of the data on the US Department of Education's [College Scorecard](https://collegescorecard.ed.gov/data/).
+ I used two main references to produce the charts in the dashboard Tom Bishop's [Highcharter Cookbook](https://www.tmbish.me/lab/highcharter-cookbook/) and Joshua Kunst Fuentes' [blog](http://jkunst.com/blog/posts/2019-02-04-using-tooltips-in-unexpected-ways/)

## Contact Me

|**Contact Method**  |                          |
| -------------------| -------------------------|
| Professional Email | cedric.lary1@gmail.com   |
