# Code and output for a flex dashboard using data from the Great British Bakeoff!

On the left is a short blurb about the data and what can be found on the 
dashboard.

On the top is an interactive time series graph showing the show ratings for each
series. The shaded regions show dates when episodes were actively coming out. 
Dashed lines show when the show changed stations. Use the toggle bar on the 
bottom to zoom in on specific dates/series.

On the bottom left an interactive map of bakers hometowns are shown. Red dots 
indicate bakers that lost, green dots indicate series winner bakers and blue
dots show the location of the Bakeoff tent.

Ont the bottom right a data table is shown containing the top three bakers from
each series, whether they are a runner up or winner and how many times they won
star baker. Season 1 did not have any star bakers.

All data can be found in the bakeoff package:
https://cran.r-project.org/web/packages/bakeoff/index.html

This data was used for Tidy Tuesday the week of October 25, 2022:
https://github.com/rfordatascience/tidytuesday/tree/master/data/2022/2022-10-25