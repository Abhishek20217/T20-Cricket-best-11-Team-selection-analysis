# T20-Cricket-best-11-Team-selection-analysis Dashboard
## Overview
This Power BI Dashboard is created to pick 11 Best Cricket players from 2022 cricket world cup based on the live actual stats of every cricket player which is available in ESPN website. The Data Scrapping was done using BrightData website and python. This Dashboard has individual and combined performance metrics of players, which allows dynamic exploration of performance values across multiple metrics. Users can select players interactively to observe combined statistics and evaluate their overall contribution.

This Dashboard shows:
* Selection of different players to view combined statistics (best 11 selection from different teams based on actual stats)
* Instant aggregation of performance metrics
* Visualization of team vs individual contributions
* Identification of top performers based on key indicators

## Dataset Used
<a href="https://github.com/Abhishek20217/T20-Cricket-best-11-Team-selection-analysis/blob/main/dim_match_summary.csv"> Dim Match summary </a>
<a href="https://github.com/Abhishek20217/T20-Cricket-best-11-Team-selection-analysis/blob/main/dim_players.csv"> Dim Players </a>
<a href="https://github.com/Abhishek20217/T20-Cricket-best-11-Team-selection-analysis/blob/main/fact_bating_summary.csv"> Fact Batting summary </a>
<a href="https://github.com/Abhishek20217/T20-Cricket-best-11-Team-selection-analysis/blob/main/fact_bowling_summary.csv"> Fact Bowling summary </a>

## Power BI Visuals used
* Slicers – For selecting individual or multiple players to analyze combined stats
* Card visuals – To show high-level metrics [ For batting (batting average, batting strike rate, Average balls faced, Boundary %), For bowling (bowling average, bowling strike rate, Balls bowled, Dot ball%)
* Table or Matrix visual – For comparing individual and combined performance.
* KPI Indicators – To highlight top performances.
* Header/Label visuals – For segmentation like “Combined Performance” or “Team Performance”

## Key Insights
### Best 11 players 
* Users can select 11 players using the slicers and Power BI will dynamically display the combined metrices like batting avg, batting strike rate,Average balls faced, Bolwing average, dot balls bowled, bowling average, economy.

### Different position analysis
* Power Hitters/ Openers.
* Anchors/ Middle Order.
* Finishers/ Lower Order Anchors.
* All Rounders/ Lower middle Order.
* Specialist Bolwers/ Tail Enders.

## Dashboard Interactions
* Player names are clickable – selection dynamically updates performance visuals.
* Cards and charts update in real-time based on selections.
* Combined metrics help in evaluating synergy between selected players.

## Use Cases
* Analyze which player combinations yield the best combined performance.
* Understand team dependency on key players by comparing individual vs team stats.
* Support coaching decisions, substitution strategies, and lineup optimization.
* Enable scouts to assess impact combinations and talent synergy

## Future Scope
* Add Time-based filtering to assess performance across matches or Years.
* Integrate win/loss outcomes for deeper contextual analysis.
* Use forecasting models to predict performance trends.
* Visualize comparison heatmaps between selected players.

## Dashboard Interaction
<a href="https://github.com/Abhishek20217/T20-Cricket-best-11-Team-selection-analysis/blob/main/T20%20world%20cup%20Best%20playing%2011%20analysis.pbix"> View Dashboard </a>

## Dashboard Preview
![1](https://github.com/user-attachments/assets/4eae2d95-5e78-42e6-9e08-555856296947)
![2](https://github.com/user-attachments/assets/616d2f4a-de67-46a2-94ae-5910e096f682)
![3](https://github.com/user-attachments/assets/b9e959ba-bb1c-4a69-b83f-729766bbdada)
![4](https://github.com/user-attachments/assets/0961ebe8-515a-43e3-892a-3045ef550ade)
![5](https://github.com/user-attachments/assets/17c94584-331d-4b88-a932-344f6f2b9e25)
![6](https://github.com/user-attachments/assets/b7b33489-643d-400b-8b33-2c1ac3c532e6)

## Conclusion
This dashboard makes it really easy to analyze how individual players perform and how they perform together. By selecting one or more players, you can instantly see their combined stats, which is super helpful for coaches, analysts, or even fans who want to dive deeper into performance insights. It also gives a good picture of how the whole team is doing, so you can compare individual or group stats against team averages. This kind of analysis can help make better decisions about team selection, substitutions, and game strategies.



