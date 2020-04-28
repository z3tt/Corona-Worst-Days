# The Worst Days: Confirmed Daily Deaths due to COVID-19 So Far

Repository of the latest visualizations showing confirmed daily deaths worldwide and per country relative to each's worst day. <br>

* You can find more background on the idea, pros and cons of this visualization and some general thoughts on how to design visualizations dealing with COVID-19 on [my blog](https://cedricscherer.netlify.com/2020/03/31/corona-covid-19-death-tolls-worst-day-so-far/).<br><br>

* All visualizations include only countries with 50 or more confirmed daily deaths due to COIVD-19.

* On April 17th 2020, officials in Wuhan, China, revised the city´s coronavirus death toll retrospectively; the deaths have been added proportionally to the daily confirmed deaths of China until that date.

***

## Heatmaps

### Countries ranked by days since worst day so far

![./plots/corona_heat_trend_latest_1.png](https://github.com/Z3tt/Corona-Daily-Deaths-Animation/raw/master/plots/corona_heat_trend_latest_1.png)<br><br>

##

### Countries ranked by day of first confirmed death

![./plots/corona_heat_begin_latest_1.png](https://raw.githubusercontent.com/Z3tt/Corona-Daily-Deaths-Animation/master/plots/corona_heat_begin_latest_1.png)<br><br>

#### As Animation:
![./plots/corona_heat_begin.gif](https://github.com/Z3tt/Corona-Daily-Deaths-Animation/raw/master/plots/corona_heat_begin.gif)<br><br>

##

### Countries ranked by total number of confirmed deaths

![./plots/corona_heat_sum_latest_1.png](https://raw.githubusercontent.com/Z3tt/Corona-Daily-Deaths-Animation/master/plots/corona_heat_sum_latest_1.png)<br><br>

#### As Animation:
![./plots/corona_heat_sum.gif](https://github.com/Z3tt/Corona-Daily-Deaths-Animation/raw/master/plots/corona_heat_sum.gif)<br><br>

***

## Trajectories

![./plots/corona_trajectory_facet_1.png](https://github.com/Z3tt/Corona-Daily-Deaths-Animation/raw/master/plots/corona_trajectory_facet_1.png)<br>

***

## World Tile Map

![./plots/corona_map_latest_1.png](https://github.com/Z3tt/Corona-Daily-Deaths-Animation/raw/master/plots/corona_map_latest_1.png)<br>

#### As Animation:
![./plots/corona_map.gif](https://github.com/Z3tt/Corona-Daily-Deaths-Animation/raw/master/plots/corona_map.gif)<br>

##

### World Tile Map showing Day of First Confirmed Death
![./plots/corona_map_date_1.png](https://github.com/Z3tt/Corona-Daily-Deaths-Animation/raw/master/plots/corona_map_date_1.png)<br>

***

## Tools:

* I prepared the data with the help of the programming language `R` using the `tidyverse` package collection and the packages `lubridate` and `zoo`

* I created the visualizations using the `R` graphic library `ggplot2` plus the packages `ggtext`, `showtext`, `rcartocolor`, and `gghighlight`. The animations were created from the static plots using `ImageMagick` in R via the  `magick` package.<br><br>

***

#### Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)
<div style="width:300px; height:200px">
<img src=https://camo.githubusercontent.com/00f7814990f36f84c5ea74cba887385d8a2f36be/68747470733a2f2f646f63732e636c6f7564706f7373652e636f6d2f696d616765732f63632d62792d6e632d73612e706e67 alt="" height="42">
</div>
