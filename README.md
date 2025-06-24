# NBA Free Agent Contracts Analysis (R)

This project explores what player statistics most significantly impact NBA free agent contract values. Using R for data wrangling, visualization, and modeling, the goal was to understand the relationship between player performance and contract size.

---

## Project Summary

- Collected and analyzed data on 194 NBA players currently on free agent contracts.
- Focused exclusively on non-rookie, non-extension contracts (pure free agency deals).
- Merged 45 explanatory variables from standard and advanced player statistics.
- Built a linear regression model using backward elimination to identify key predictors of salary.

---

## Key Findings

10 significant predictors of contract salary:

**Basic Stats**:  
- Games Started (GS)  
- Minutes Played (MP)  
- Assists (AST)  
- Personal Fouls (PF)  
- Points Per Game (PTS)

**Advanced Stats**:  
- Total Rebound % (TRB%)  
- Usage Rate (USG%)  
- Offensive Box Plus/Minus (OBPM)  
- Defensive Box Plus/Minus (DBPM)  
- Overall BPM

The final model achieved 88.93% accuracy using a train-test split (70/30).

---

## Tools Used

- R programming language  
  - dplyr, ggplot2, and base R functions  
- Excel for data organization  
- PowerPoint for visual storytelling  
- Data sourced from:  
  - https://www.basketball-reference.com  
  - https://www.spotrac.com/nba/contracts/

---

## Files

- `NBA contracts ANALYSIS FINAL.pptx` – Final slide presentation with charts, regression output, and model insights

---

## Takeaway

Despite the cliché that "defense wins championships," this model shows that offensive production and usage are stronger predictors of free agent salaries — though defensive contributions like DBPM still play a supporting role.

---

## Contact

Created by Sean Volpi – B.S. in Statistics  
