# Survival_Analysis_League_of_Legends
I always die!! 

## Introduction
League of Legends (LoL) is a multiplayer online battle arena video game developed and published by Riot Games for Microsoft Windows and macOS. In League of Legends, players assume the role of a "champion" with unique abilities and battle against a team of other player- or computer-controlled champions. The goal is usually to destroy the opposing team's "Nexus", a structure that lies at the heart of a base protected by defensive structures, although other distinct game modes exist as well with varying objectives, rules, and maps. 
Each League of Legends match is discrete, with all champions starting off relatively weak but increasing in strength by accumulating items and experience over the course of the game. This dataset contains the first 10min. stats of approx. 10k ranked games (SOLO QUEUE) from a high ELO (DIAMOND I to MASTER). Players have roughly the same level. 
The dataset we are working on has 19 features per team (38 in total) collected after 10min in-game. This includes kills, deaths, gold, experience, level… The column blueWins is the target value (the value we are trying to predict). A value of 1 means the blue team has won. THis project aims to predict which features are more correlated with winning.
