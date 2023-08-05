# Overwatch-League-EDA
Exploration of Overwatch League dataset to find what variables are the most informative when predicting the outcome of Overwatch League games for individual players.

The purpose of this project is exploratory analysis of the Overwatch League. My aim is to find which variables are significant predictors of winning matches. This study with inform the variables I use building the final model of predicting the outcome of Overwatch League matches in another project. 


## Necessary Domain Knowledge:

The Overwatch league is an international Esports league ran and owned by Blizzard. The league is comprised of 19 city-based teams. The matches are formatted in best of 5 games. With each game being played on a unique map. The maps range from 1 to 4 rounds. In this project, I am only interested in the winners of maps and matches, not rounds.

Each team consists of 5 players, each having unique roles. A tank, two damage dealing players, and two healing/support players.

## Data

I will be using two sets of data. "phs-2023/2022" and "watch_map_stats". The "phs" dataset are player statitistics, while "watch_map_stats" are the map statistics. The payer statistics include the predictor variables of the players performance, while the map statistics include the response variable (what I aim on predicting) the outcome of each match. The data is all sourced from the [Overwatch League statistics page](https://overwatchleague.com/en-us/statslab). 

(Note, I am only using 2022 and 2023, as overwatch 2 was released in 2022, which came with significant balance changes, most notably changing the number of players in each team from 6 to 5, rendering all data pre 2022 useless here). \
