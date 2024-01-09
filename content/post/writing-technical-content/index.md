---
title: "Reproducible Interactive Dashboard Design Using R and R Markdown :-)"
description: |
  ACME 2022
author:
  - name: Zhenning "Jimmy" Xu
date: 2022-03-13
output:
  distill::distill_article:
    self_contained: false
---


```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = FALSE)
```

Distill is a publication format for scientific and technical writing, native to the web.

Learn more about using Distill at <https://rstudio.github.io/distill>.


???

Image credit: [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Sharingan_triple.svg)

---
class: center, middle

# xaringan

### /ʃaː.'riŋ.ɡan/

---
class: inverse, center, middle

# Get Started

---
# Interactive dashboards

## Please find the interactive dashboard you will be trying to build today 

- Link to the dashboard we will be building together - https://rpubs.com/utjimmyx/Flexdashboard_2021

## Examples of complex dashboards 

- How California Uses Shiny in Production to Fight COVID-19 - https://www.rstudio.com/blog/using-shiny-in-production-to-monitor-covid-19/

- A simulation dashboard I built using ShinyR - https://utjimmyx.shinyapps.io/bullwhip2/

---

# Using R or R Studio for data analytics and reporting

### Assumptions
- you have a laptop and stable internet connections
- you can Google search
- you used Excel before

### R has an awesome community
- There are thousands of Meetup groups around the world
- The Meetup I started organizing from 2019- https://www.meetup.com/Bakersfield-Data-Analytics-Using-R-Meetup-Group/


---
background-image: url(`r xaringan:::karl`)
background-position: 50% 50%
class: center, bottom, inverse

# You only live once!

---
# What are we going to cover today?

- What is a dashboard?  
- Why R or R Studio?
- Why R Markdown?
- Interactive plotting and mapping using R
- Modern dashboard design packages (e.g., the modern react js web framework) available in R
- Hands-on exercise - Design your own dashboard using Flexdashboard

It is important to be familiar with R Studio before you can understand the options in **dashboard design**using **Flexdashboard**, **Plotly**, **mapbox**, **ShinyR**, etc.

- Come on... You do not need to pay hefty subscription fees for SPSS, SAS, and Tableau anymore! Well, R allows you to do everything you need to do in data analytics, big data analytics, and machine learning.
---

# Easy dashboard with Flexdashboard?!

## Why using a dashboard?

- Cool and easy way to create a dashboard without paying subscription fees 
- Uses R Studio (or R Studio Cloud; free) and R Markdown (free)

## Benifits
- CSS stylization; htmlwidgets; base, lattice, and grid graphics; tabular data; gauges and value boxes; and text annotations
- row and column-based layouts
- Interactive and easy to adapt for purposes.

You can see an introduction of Flexdashboard from [its homepage](https://pkgs.rstudio.com/flexdashboard/). You should read the information and try it on your own at least once to know how to

- create a R Markdown document;

- format a document (e.g. text alignment);

- configure the layout;

- and most importantly, Google search and use Stackoverflow or Stackoverexchange.

---
background-image: url(`r xaringan:::karl`)
background-size: cover
class: center, bottom, inverse

# I was so happy to have discovered RStudio and Flexdashboard at the 2022 ACME Conference!

---
# Design interactive maps using R packages like Leaflet, Mapbox, etc.

```{r out.width='100%', fig.height=6, eval=require('leaflet')}
library(leaflet)
m <- leaflet() %>% addTiles()
m %>%
  # Central Park
fitBounds(-73.9, 40.75, -73.95,40.8)
```

---

# Let's design an interactive dashboard together!

- Steps and procedures 
- How to use R Studio Cloud?
- R Studio Cloud - Register (or log into the platform using your email credentials) - > File -> New File -> R Markdown -> Install packages - > click the "knit" button -> Publish results
- Please copy my syntax at my Github website
- Introduction to the dataset
- Install the packages
- Register an account at Rpubs.com
- Publish your results as an HTML page for free

It is important to be familiar with R Studio before you can understand the options in **dashboard design**using **Flexdashboard**, **Plotly**, **mapbox**, **ShinyR**, etc.

Come on... You do not need to pay hefty subscription fees for SPSS, SAS, and Tableau anymore! Well, R allows you to do everything you need to do in data analytics, big data analytics, and machine learning.

---


# Thanks!

Slides for today can be accessed at my Rpubs.com website [**rpubs.com**](https://rpubs.com/utjimmyx).

Syntax for our dashboard design tutorial can be accessed at my Github website [**my Github website**](https://github.com/utjimmyx).


