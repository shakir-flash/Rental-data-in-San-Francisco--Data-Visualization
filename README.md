# Project- Data Visualization

This project is about uing R to vislualize and plot the rental data in the city of San Francisco. 

##Problem statement
    **Rental apartments in SF.** The data for this exercise comes from 
    TidyTuesday and it's on rental prices in San Francisco. You can find 
    out more about the dataset by inspecting its documentation 
    [here](https://github.com/rfordatascience/tidytuesday/tree/master/data/2022/2022-07-05).
    This project is to create a visualization that will help compare the distribution
    of rental prices (`price`) per bedroom (`beds`) across neighborhoods 
    (`nhood`) in the city of San Francisco (`city == "san francisco"`), 
    over time. Limit of analysis to rentals where the full unit is available,
    i.e. (`room_in_apt	== 0`). 

     ``` {r}
install.packages("pacman")
install.packages("tidyverse")
install.packages("dplyr")
install.packages("ggplot2")
pacman::p_load("tidyverse")
    ```
    

5.  **Napoleon’s march.** The instructions for this exercise are simple:
    recreate the Napoleon’s march plot by Charles John Minard in
    ggplot2. The data is provided as a list, saved as `napoleon.rds`.
    Read it in using `read_rds()`. This object has three elements:
    `cities`, `temperatures`, and `troops`. Each of these is a data
    frame, and the three of them combined contain all of the data you
    need to recreate the visualization. Your goal isn’t to create an
    exact replica of the original plot, but to get as close to it as you
    can using code you understand and can describe articulately in your
    response. I’ll be the first to say that if you google “Napoleon’s
    march in ggplot2”, you’ll find a bunch of blog posts, tutorials,
    etc. that walk you through how to recreate this visualization with
    ggplot2. So you might be thinking, “why am I being asked to copy
    something off the internet for my homework?” Well, this is an
    exercise in (1) working with web resources and citing them
    properly, (2) understanding someone else’s ggplot2 code and
    reproducing their work, (3) describing what that code does in your
    own words, and finally (4) putting some final touches to make the
    final product your own. Some more guidelines below:

    -   You should make sure your response properly cites all of the
        resources you use. I’m defining “use” to include “browse, read,
        get inspired by, or directly borrow snippets of code from”. You
        don’t need to worry about formal citations, it’s okay to make a
        list with links to your resources and provide a brief summary of
        how you used each one.
    -   For this exercise, you’re asked to describe what your code does
        (instead of interpreting the visualization, since we already did
        that in class). If you write the code, it should be
        straightforward for you to describe it. If you borrow any code
        from outside resources, you need to understand what that code
        does, and describe it, ***in your own words***. (This is
        important, you’re allowed to use found code, but you are not
        allowed to copy someone’s blog post or tutorial as your
        description of their code.)
    -   Finally, you should personalize the visualization with your own
        touch. You can do this in a myriad of ways, e.g., change colors,
        annotations, labels, etc. This change should be made to make the
        plot more like the original in some way. You need to explicitly
        call out what change you made and why you made it.
