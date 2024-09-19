# Among Us - Exploratory Data Analysis 🎮🚀

## OVERVIEW 🌟
This Notebook contains an exploratory data analysis (EDA) of gameplay statistics from the popular multiplayer game, **Among Us**. Originally released in 2018, the game surged in popularity during the summer of 2020, resulting in a wealth of data regarding player performance and game dynamics.

---

## DATASET DESCRIPTION 📊
The dataset includes the following columns:

- **Game Completed Date** 🗓️: The date when the game was completed.
- **Team** 🤝: The team of the player (Crewmate or Imposter).
- **Outcome** 🏆: The result of the game (Win, Loss, etc.).
- **Tasks Completed** ✅: The number of tasks completed by a Crewmate during the game.
- **All Tasks Completed** ✔️: A boolean indicating whether all tasks were completed by the Crewmates during the game.
- **Murdered** ⚰️: A boolean indicating whether a Crewmate was murdered.
- **Imposter Kills** 🔪: The number of Crewmates killed by Imposters during the game.
- **Game Length** ⏳: The total duration of the game.
- **Ejected** 🚪: A boolean indicating whether a player was ejected during the game.
- **Sabotages Fixed** 🔧: The number of sabotages that were fixed by Crewmates.
- **Time to Complete All Tasks** ⏲️: The total time taken by Crewmates to complete all tasks.
- **Rank Change** 📈: The change in competitive rank after playing three games, influenced by performance in each game.
- **Region/Game Code** 🌍: The server region and game code of the match.

---

## DATA PREPROCESSING 👨🏻‍🔧
The dataset undergoes several preprocessing steps to enhance analysis, including splitting the game date and time, formatting game metrics, and preparing for visualization.

---

## EXPLORATORY DATA ANALYSIS 📊

### Individual Analysis - Time to Complete All Tasks
*Comparison of task completion time between successful and failed games.* 👍🏻👎🏻

### Crewmate vs. Imposter Performance
*Visualizing win rates and kill counts for Crewmates and Imposters.* 🏆🔪

### Ejection Analysis: Crewmates vs. Imposters ⏏️📊
*Analysis of how often players are ejected based on their team.*

### Players' Winning vs. Losing Statistics 📊🏅
*Bar chart comparing wins and losses for each player.*

---

## KEY INSIGHTS 🔍
- **Task Completion**: Winning games often correlate with higher task completion rates.
- **Imposter Strategy**: Successful Imposters have a higher number of kills.
- **Ejection Trends**: A noticeable difference exists in the number of ejections between Crewmates and Imposters.

---

## FUTURE WORK 🚧
This analysis is a work in progress. Future improvements could include:
- More granular insights into specific player behaviors.
- Enhanced visualizations to illustrate trends over time.
- Integration of player communication data to better understand game dynamics.

---

## CONCLUSION 🎉
This EDA provides valuable insights into gameplay dynamics in **Among Us**, helping players understand strategies that lead to victory and enhance overall gameplay experience. 

---
