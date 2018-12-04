# Kaggle-PUBG-Prediction
## Introduction
Battle Royale-style video games have taken the world by storm. 100 players are dropped onto an island empty-handed and must explore, scavenge, and eliminate other players until only one is left standing, all while the play zone continues to shrink. Player Unknown’s Battlegrounds (PUBG) has enjoyed massive popularity.

The team at PUBG has made official game data available for the public to explore and scavenge outside of "The Blue Circle." Kaggle collected data made possible through the PUBG Developer API. With the provided data, we were trying to predict final placement from final in-game stats and initial player ratings.

## Data Description
In a PUBG game, up to 100 players start in each match (matchId). Players can be on teams (groupId) which get ranked at the end of the game (winPlacePerc) based on how many other teams are still alive when they are eliminated. In game, players can pick up different munitions, revive downed-but-not-out (knocked) teammates, drive vehicles, swim, run, shoot, and experience all of the consequences -- such as falling too far or running themselves over and eliminating themselves.

In the Kaggle website, the original data was pre-split into training and testing dataset. We will be using the whole training set in the project since the target variable was missing in the testing dataset due the Kaggle rule. After checking the missing value, the dataset was completed. The whole training dataset includes 4357336 cases which refer to every single player’s record in every game, and the dataset contains 26 columns including target variable, winning place percentage.
