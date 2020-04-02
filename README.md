# NBA-Wining-Rate---FE-Prediction
Use plyers' stats, team and year fixed effect to predict team wining rate

The reason to study this topic:
Help understand what makes a strong team that stands out winning more games
Potential insights for team management on better player recruitment strategies
Possible usage for NBA sports gambling

Type of Our Predictive Problem: Regression Problem – target variable “winning PCT” (continuous valued, range from 0 to 1)

Some important concepts in the data & modeling process:
- PER: Player Efficiency Rating; sums up all a player’s positive accomplishments, subtracts the negative accomplishments, and returns a per-minute rating of a player’s performance
-DWS: Defensive Win Shares, a player statistic that divvy up credit for a team’s success onto individual players on the team; calculated using player, team and league-wide statistics and the sum of player win shares on a given team roughly equivalent to the team’s win total for the season
-”TS%”: True Shooting Percentage, formula: ”Points/(2*True Shooting Attempts)”; takes into account field goals, 3-point field goals, and free throws
-“FT%”: Free Throw Percentage, formula: “Free Throws/Free Throw Attempts”
-”TOV%”: Turnover Percentage, formula: “100*Turnovers/(Field Goal Attempts + 0.44*Free Throws Attempts + Turnovers)”
