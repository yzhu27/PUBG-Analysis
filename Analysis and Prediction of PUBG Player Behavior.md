# Analysis and Prediction of PUBG Player Behavior



## Dataset Description

https://www.kaggle.com/datasets/skihikingkevin/pubg-match-deaths

#### PlayerUnknown's Battlegrounds

PUBG is a first/third-person shooter battle royale style game that matches over 90 players on a large island where teams and players fight to the death until one remains. Players are airdropped from an airplane onto the island where they are to scavenge towns and buildings for weapons, ammo, armor and first-aid. Players will then decide to either fight or hide with the ultimate goal of being the last one standing.

#### The Dataset

This dataset provides two zips: aggregate and deaths.

- In deaths, the files record every death that occurred within the 720k matches. That is, each row documents an event where a player has died in the match.
- In aggregate, each match's meta information and player statistics are summarized (as provided by pubg). It includes various aggregate statistics such as player kills, damage, distance walked, etc as well as metadata on the match itself such as queue size, fpp/tpp, date, etc.

The uncompressed data is divided into 5 chunks of approximately 2gb each. For details on columns, please see the file descriptions.



## Project Idea

The goal of this project is to analyze player behavior in the popular game Player Unknown's Battlegrounds (PUBG) and use machine learning techniques to classify cheaters and predict recommended strategies for gamers in the game. This is a relevant challenge as cheating is a common problem in online games, and identifying cheaters is important to maintain a fair and enjoyable gaming experience for all players.

We plan to first perform exploratory data analysis on the PUBG dataset to gain a better understanding of player behavior and gameplay patterns. This may include analyzing factors such as player rankings, game modes, and weapon usage. We will also investigate correlations between different attributes in the data to identify any useful patterns.

To identify cheaters, we plan to use machine learning algorithms such as decision trees and random forests to analyze player data and detect anomalous behavior. We will compare the performance of different classification models and feature representation techniques, such as one-hot encoding and word embeddings, to determine the most effective approach.

In addition to identifying cheaters, we also plan to use the data to predict recommended strategies for gamers in the game. This may involve analyzing successful strategies used by top players and using this information to recommend tactics for other players to improve their performance.

The step-by-step approach will include pre-processing of the PUBG data by handling missing values, removing outliers, and feature scaling. We will also perform feature engineering to extract meaningful information from the raw data.

Overall, this project aims to use machine learning techniques to analyze player behavior in PUBG, classify cheaters, and predict recommended strategies for gamers. By doing so, we hope to contribute to a fair and enjoyable gaming experience for all players.



## Software Specification

Visual Studio Code, Python3, Jupyter, PyTorch, Scikit-Learn, Pandas, TensorFlow, Keras, Matplotlib

## Work Division



## Paper to Read

1. Ghazali N F, Sanat N, As' ari M A. Esports Analytics on PlayerUnknown's Battlegrounds Player Placement Prediction using Machine Learning[J]. International Journal of Human and Technology Interaction (IJHaTI), 2021, 5(1): 17-28.
2. Rokad B, Karumudi T, Acharya O, et al. Survival of the Fittest in PlayerUnknown BattleGround[J]. arXiv preprint arXiv:1905.06052, 2019.
3. Indulkar Y. PUBG Winner Ranking Prediction using R Interface ‘h2o’Scalable Machine Learning Platform[C]//2021 International Conference on Emerging Smart Computing and Informatics (ESCI). IEEE, 2021: 300-305.
4. Mamulpet M M. Pubg Winner Placement Prediction Using Artificial Neural Network[J]. Int. J. Eng. Appl. Sci. Technol, 2019, 3(12): 107-118.
5. Gałka P, Strzelecki A. How randomness affects player ability to predict the chance to win at PlayerUnknown’s Battlegrounds (PUBG)[J]. The Computer Games Journal, 2021, 10: 1-18.

## Midterm Milestone