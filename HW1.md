# HW 1

For this dataset we will use the following data set containing location
of elk in Banff National Park (Canada). Additional information can be
found at [movebank
link](https://datarepository.movebank.org/entities/datapackage/aed22923-281d-4583-aefd-140f1497539a/full).

``` r
library(tidyverse)
library(knitr)
elk <- read_csv('https://raw.githubusercontent.com/Stat534/data/refs/heads/main/elk.csv')
```

## Question 1 (2 points)

How many unique elk (based on `tag-local-identifier`) are in the
dataset?

## Question 2 (2 points)

What is the maximum number of locations for a single elk?

## Question 3 (4 points)

Use leaflet to create a figure that shows the location of each elk.
Filter your dataset to only include the first location (using the
minimum `event-id`) for each elk.

## Question 4 (4 points)

Use `ggmap` to plot all of the locations of elk (`tag-local-identifier`)
`GR103`. Create a density plot or heatmap.
