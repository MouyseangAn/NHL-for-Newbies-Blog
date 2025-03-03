# From Newbie to Know-it-all: The Hockey Game

## Project Overview
This blog introduces ice hockey basics and analyzes player/team performance using data from the Colorado Avalanche's 2022-2023 season. Aimed at newcomers, it combines rule explanations with statistical analysis in R to answer key questions about player contributions and team success. The analysis explores correlations between metrics like goals, assists, and power play goals, while also evaluating goalie performance.

## Key Analyses
1. **Player Performance**:  
   - Correlation between goals, assists, plus/minus, and total points.  
   - Impact of power play goals on team success.  
2. **Goalie Performance**:  
   - Predictive power of save percentage (`SV%`) and goals against average (`GAA`) on team wins.  

## Tools Used
- **R Libraries**: `tidyverse`, `dplyr`, `ggplot2`.  
- **Data Sources**: [Hockey Reference](https://www.hockey-reference.com/teams/COL/2023.html) (Colorado Avalanche player and goalie stats).  

## Key Findings
- **Player Metrics**:  
  - Goals (`G`) and assists (`A`) show **strong positive correlations** with points (`PTS`), indicating their critical role in player success.  
  - Power play goals (`PP`) have a **positive linear relationship** with points, highlighting their importance in team strategy.  
- **Goalie Metrics**:  
  - Save percentage and goals against average did **not significantly predict wins**, likely due to limited sample size.  
