# Football World Cup Winner Prediction

## 1. Introduction

Aim is to create a model which predicts the winner of the FIFA World Cup 2018.

## 2. Data

Three datasets from kaggle were used:

1. rankings.csv; <br/>
FIFA rankings from 1993 to 2018 is used to get the FIFA ranking and points for the teams, which is a monthly changing rank 
previously shown as a decent predictor of team performance. A complete variable dictionary can be found 
[here](https://www.kaggle.com/tadhgfitzgerald/fifa-international-soccer-mens-ranking-1993now) . 

2. results.csv; <br/>
International Soccer matches from 1872 to 2018 is to find out how much the difference in point, ranks 
and the current rank of the team affects the outocme of a match. A complete variable dictionary can be found 
[here](https://www.kaggle.com/martj42/international-football-results-from-1872-to-2017) . 

3. FIFA World Cup 2018 data set is to get the upcoming matches. A complete variable dictionary can be found 
[here](https://www.kaggle.com/datasets/ahmedelnaggar/fifa-worldcup-2018-dataset) . 

## 3. Feature Selection & Generation

- is_won: This is a boolean type feature, that is tried to be predicted. "score_difference > 0" is the formula, which means draws are also treated as losses.
- rank_difference: "rank_home - rank_away" is the formula.
- average_rank: "(rank_home + rank_away)/2" is the formula.
- point_difference: "weighted_points_home - weighted_points_away" is the formula.
- score_difference: "home_score - away_score" is the formula.
- is_stake: This is a boolean type feature. "tournament != 'Friendly'" is the formula. Because friendly games have different dynamics, it would be much better to flag them.

## 4. Modelling

## 5. Simulation

## 6. Visualization