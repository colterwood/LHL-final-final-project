# LHL-final-final-project
The intent is to create a profitable sportsbetting model for WNBA totals and spreads.

## Hypothesis:
Utilizing historical game data, past player performances, and play by play data we will have a model that can determine which WNBA lines to bet to be profitable over time.

## Data:
Utilizing [Basketball-Reference](https://www.basketball-reference.com/) I have created the following dataframes:

##### 2024_basketball_reference_gamelog.csv
-contains gamelogs for each team from the 2024 season

##### 2024_basketball_reference_gamelog-advanced.csv
-contains advanced gamelog data for each team from the 2024 season

##### 2024_player_gamelogs.csv
-contains gamelog data for each player that played in the 2024 season

##### player_data.csv
-contains player data for each player that played in the 2024 season
-data is broken down by season and also contains a career breakdown
-tables used in this data include Per Game (per_game), Per 36 Minutes (per_minute), Per 100 Poss (per_poss), Advanced (advanced), Play-by-Play (pbp), Shooting (shooting)
