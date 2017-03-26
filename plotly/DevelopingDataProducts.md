Developing Data Products - plotly
========================================================
author: Kevin E. D'Elia
date: November 12, 2016
autosize: true

Number of phones by Continent/Geographic Areas in the World
========================================================



This is an interactive map created using the [plotly](https://plot.ly/r/) package.  It shows a statistical summary via a box plot of the number of phones in existence across world geographic areas.  Data was obtained from the **WorldPhones** dataset available in R.

Slide With Code
========================================================



```r
# Create data frame
world.phones <- as.data.frame(WorldPhones)

# Use dplyr to reformat data into a more usable structure
by.country <- gather(world.phones, key, country)
```

Slide With Plot
========================================================




```
Error in file(con, "rb") : cannot open the connection
```
