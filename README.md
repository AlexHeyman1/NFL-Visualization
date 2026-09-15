# The Evolution of the Quarterback Position in the NFL

## Overview
This project explores how the NFL quarterback position evolved from the 2012 through 2024 seasons, with a focus on changes in passing, rushing, efficiency, and team success.

Using 13 seasons of quarterback data, I created a series of static and interactive visualizations to examine whether quarterbacks have become more versatile over time and whether those changes are associated with a greater likelihood of reaching the postseason.

## Full Project

[View the NFL Quarterback Visualization Report](https://alexheyman1.github.io/NFL-Visualization/)

## Research Questions

The project focuses on three main questions:

1. How has the quarterback position evolved in terms of passing versus rushing?
2. What quarterback statistics have changed most noticeably over the past 13 seasons?
3. Have more versatile quarterbacks experienced greater team success?

## Data

The analysis includes regular-season quarterback data from 2012–2024.

To focus on quarterbacks with meaningful playing time, the primary analysis includes players who:

- Played in at least 8 games during a season
- Recorded at least 100 passing attempts
- Participated during the regular season

Quarterback performance was analyzed using passing, rushing, efficiency, and postseason variables.

## Tools & Technologies

- R — data cleaning, transformation, analysis, and visualization
- ggplot2 — static statistical visualizations
- Plotly — interactive and animated visualizations
- Shiny — interactive applications and user-controlled analysis
- Tableau — interactive dashboards and exploratory visualization


## Visualizations

The project uses several visualization techniques to explore changes in quarterback performance, including:

- Time-series and grouped comparisons across seasons
- Passing vs. rushing scatterplots
- Animated visualizations showing changes over time
- Box plots comparing playoff and non-playoff quarterbacks
- Interactive Shiny applications with user-selected statistics and filters
- Tableau dashboards for exploring quarterback trends across seasons

## Key Findings

The analysis shows a noticeable shift toward quarterbacks contributing more as runners. Later seasons contain substantially more quarterbacks with high rushing production than earlier periods.

Passing volume, however, did not increase alongside this shift. Median passing attempts per game were generally lower from 2021–2023 than during much of the 2012–2020 period.

Quarterbacks who reached the postseason generally performed better on passing-efficiency measures such as completion percentage, yards per attempt, and touchdown-to-interception ratio. These measures showed a clearer relationship with postseason success than passing volume alone.

Quarterbacks with greater rushing production also appeared more likely to reach the postseason, although rushing efficiency by itself was not a consistent indicator of postseason success.

Overall, the results suggest that the quarterback position has become more versatile, while efficient passing remains strongly associated with team success.

## Interactive Applications

This project includes interactive Shiny applications and a Tableau dashboard that allow users to explore quarterback statistics, seasons, and postseason performance.

### Shiny Apps
- [Quarterback Attempts & Postseason App](https://alexheyman.shinyapps.io/Stat3280Shiny1/)
- [Quarterback Efficiency & Postseason App](https://alexheyman.shinyapps.io/project/)

### Tableau Dashboard
[Explore the Interactive Dashboard](https://public.tableau.com/app/profile/alex.heyman/viz/FinalStat3280Tableau1/Dashboard1)

