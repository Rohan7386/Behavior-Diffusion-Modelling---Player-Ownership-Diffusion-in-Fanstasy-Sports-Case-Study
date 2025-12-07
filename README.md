# Behavior-Diffusion-Modelling---Player-Ownership-Diffusion-in-Fanstasy-Sports-Case-Study
Behavior Diffusion Modelling: Understanding Ownership Diffusion in Fantasy Sports using Neural Networks’ Prediction 

# Project Overview
Fantasy sports represent an emerging entertainment opportunity that better involves the fans in the respective sports. Through the aspect of the purchase and sale of players in the fantasy leagues, the behavior diffusion in virtual entertainment can be studied and predicted. In this project, the diffusion of the ownership of players in the Fantasy Premier League (FPL), will be explored with predictability evaluated through social influence (in terms of respective club popularity), market movements (in terms of player pricings in the fantasy leagues), player performance (in terms of player performance metrics) and game metrics (in terms of game difficulty and team strength). 

Network analysis was be employed to explore the behavior diffusion for player ownership in the FPL for the current 2025/2026 season. Social Network Analysis formed the initial stage in the network analysis, where the co-ownership can be evaluated from a social behavior point of view. Three types of social network analyses provided insight for the diffusion of player ownership: structural analysis (distribution of players across the diffusion network), relational analysis (strength of the co-ownership of players) and dynamic analysis (diffusion of ownership over time for the game weeks in the current season). From the foundational network insights from the social network analysis, the project developed regression neural network models for the prediction of the diffusion of player ownership; three neural network models will be applied for the prediction and compared for optimal prediction.

# Data Sources
The following three data sources will be utilized for collecting information:

- FPL API (https://fantasy.premierleague.com/api/bootstrap-static)
- GitHub (https://github.com/FPLYogi/FPL-Data/tree/main/.github)
- CIES Football Observatory (https://football-observatory.com/WeeklyPost508)

![Data Sources](https://github.com/Rohan7386/Behavior-Diffusion-Modelling---Player-Ownership-Diffusion-in-Fanstasy-Sports-Case-Study/blob/main/Data%20Sources.png)

# Workflow Summary

The chart below summarizes the workflow for the project.

![Work Flow](https://github.com/Rohan7386/Behavior-Diffusion-Modelling---Player-Ownership-Diffusion-in-Fanstasy-Sports-Case-Study/blob/main/Modelling.png)

# Technology Used 

- Languages Used: Python
- Additional Softwares: Tableau, Mermaid
- Data Sources: FPL API, GitHub, CIES Football Observatory

# Results Summary 

![Descriptive Statistics](https://github.com/Rohan7386/Behavior-Diffusion-Modelling---Player-Ownership-Diffusion-in-Fanstasy-Sports-Case-Study/blob/main/Dashboard1-2.png)

![Social Network Analysis](https://github.com/Rohan7386/Behavior-Diffusion-Modelling---Player-Ownership-Diffusion-in-Fanstasy-Sports-Case-Study/blob/main/Dashboard3.png)

![LSTM](https://github.com/Rohan7386/Behavior-Diffusion-Modelling---Player-Ownership-Diffusion-in-Fanstasy-Sports-Case-Study/blob/main/LSTM.png)

![1D Temporal CNN](https://github.com/Rohan7386/Behavior-Diffusion-Modelling---Player-Ownership-Diffusion-in-Fanstasy-Sports-Case-Study/blob/main/1DTCNN.png)

![2D Temporal CNN](https://github.com/Rohan7386/Behavior-Diffusion-Modelling---Player-Ownership-Diffusion-in-Fanstasy-Sports-Case-Study/blob/main/2DTCNN.png)

![Metric Comparison](https://github.com/Rohan7386/Behavior-Diffusion-Modelling---Player-Ownership-Diffusion-in-Fanstasy-Sports-Case-Study/blob/main/ModelMetrics.png)

# Summary Findings

Nottingham Forest had a positive diffusion in the transfer pressure as the last season progressed.Crystal Palace has the largest transfer momentum with Crystal Palace, Manchester City and Newcastle having the largest total points momentum, so far this season.The Co-Ownership Network showed presence of three influential clusters that formed three influential communities in the diffusion of Co-Ownership. All three models showed good performance in the validation data and had low predictive power for the diffusion of Co-ownership of players in the FPL. However, the LSTM captured well the underlying noise while the Temporal CNNs overpredicted large diffusions. 

The case of Nottingham Forest for last season presents a useful case for diffusion modeling , while for this season so far, Crystal Palace presents a case study that can be compared to that of Nottingham Forest. Co-ownership network consist of clusters that form communities that can are influential in managers’ behavior in terms of player ownership. Although all three models have low prediction power, the LSTM performs best in prediction of diffusion of player ownership, with a 5.64% accuracy in the prediction of diffusion direction. 








