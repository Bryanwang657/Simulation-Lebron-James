# LeBron James Triple-Double Impact Simulation
## Project Overview
This project aims to investigate the impact of LeBron James achieving a triple-double on the Los Angeles Lakers' probability of winning a game. A triple-double involves LeBron scoring double digits in three of five statistical categories: points, rebounds, and assists. We are excluding blocks and steals, as LeBron has zero (or very few) triple-doubles that include double digits in those statistics.

## Objective
The primary objective is to construct a simulation that utilizes historical data from past seasons where LeBron recorded triple-doubles while on the Lakers. This data will help fit distributions for his scoring, rebounding, and assisting in these games, as well as for the team's overall performance metrics and those of their opponents.

## Methodology
Data Collection: Gather historical data from sources like ESPN, StatMuse, and Basketball Reference.
Data Analysis: Analyze LeBron's historical performance data to determine appropriate distributions for each key metric, such as normal or Poisson distributions.
Simulation Construction: Build a simulation that models game outcomes based on these distributions, focusing on the proportion of wins when LeBron achieves a triple-double.
Exploratory Analysis: Examine the impact of different statistical areas (points, assists, rebounds) and compare the outcomes against Western Conference and Eastern Conference teams.

## Random Inputs
The primary sources of randomness in this simulation will be:

LeBron's game-to-game performance fluctuations in points, rebounds, and assists.
Performance metrics of the Lakers and their opponents.
Outcomes
The simulation will run multiple scenarios to generate a distribution of game outcomes, informing us about the probability of a Lakers' victory under the condition of LeBron achieving a triple-double. The results will highlight the significance of LeBron's triple-double performances to the Lakers' success.

## Tools
Statistical analysis and distribution fitting
Monte Carlo simulation
Python and relevant libraries
Expected Results
The results will be reported in terms of the distribution of win probabilities, highlighting how crucial LeBron’s triple-double performances are to the Lakers' success.

## Repository Contents
LebronJames.ipynb: Jupyter Notebook containing the code and analysis for the simulation.
Data files: Historical performance data for LeBron James and the Lakers.

## Contact
Please reach out if you have any questions or feedback. We are happy to “assist”! (bad pun)
