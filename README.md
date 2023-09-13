# Project- Data Visualization

This project is about uing R to vislualize and plot the rental data in the city of San Francisco. 

##Problem statement
Rental apartments in SF. The data for this exercise comes from 
TidyTuesday and it's on rental prices in San Francisco. You can find 
out more about the dataset by inspecting its documentation 
[here](https://github.com/rfordatascience/tidytuesday/tree/master/data/2022/2022-07-05).
This project is to create a visualization that will help compare the distribution
of rental prices (`price`) per bedroom (`beds`) across neighborhoods 
(`nhood`) in the city of San Francisco (`city == "san francisco"`), 
over time. Limit of analysis to rentals where the full unit is available,
i.e. (`room_in_apt	== 0`). 

Library function used, and installation of packages:

     ``` {r}
install.packages("pacman")
install.packages("tidyverse")
install.packages("dplyr")
install.packages("ggplot2")
pacman::p_load("tidyverse")
```
    
