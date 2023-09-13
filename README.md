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
i.e. (`room_in_apt	== 0`). Year of filter is from 2010-2018

Library function used, and installation of packages:

     ``` {r}
     install.packages("pacman")
     install.packages("tidyverse")
     install.packages("dplyr")
     install.packages("ggplot2")
     pacman::p_load("tidyverse")
     ```
Plots generated from the code:

**1. Bayview neighborhood:**

![bayview](https://github.com/shakir-flash/Rental-data-in-San-Francisco-Data-Visualization/assets/59859522/237564e0-823e-4932-bda0-116d163619fd)


**2. Parkside neighborhood:**

![parkside](https://github.com/shakir-flash/Rental-data-in-San-Francisco-Data-Visualization/assets/59859522/a4861e66-7ccc-4c2a-8112-e7b351efe634)


**3. CCSF vs Russian Hill neighborhood:**

![ccsf_vs_russianhill](https://github.com/shakir-flash/Rental-data-in-San-Francisco-Data-Visualization/assets/59859522/55c807d6-454e-48d2-ab06-5527618ad46d)


**4. Sea Cliff vs Twin Peaks neighborhood:**

![seacliff_vs_twinpeaks](https://github.com/shakir-flash/Rental-data-in-San-Francisco-Data-Visualization/assets/59859522/249a2b0b-5503-4bb4-8feb-09adeb41af35)

There are three layers in the plot for the above:
1. Dotplot of all the data points in the csv file.
2. Dotplot of the median points calculated in the R code.
3. Lineplot of the median points to show the fluctuating trends in price per bedroom.

