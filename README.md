# World Cup Prediction Model

This project uses player-level statistics and position-specific analysis to estimate the outcomes of World Cup matches. Rather than relying on machine learning, we designed a structured rating and comparison system that evaluates teams based on player roles, matchups, and weighted performance metrics.

## Project Structure

- [PhaseIII.ipynb](./PhaseIII.ipynb) – Main notebook where the player evaluation logic, team comparison engine, and simulation are implemented.
- [summary_file.xlsx](./summary_file.xlsx) – Cleaned and summarized dataset containing player stats and performance metrics.
- [visualization1.png](./visualization1.png) – Bar chart showing the average team strength (aggregated player rating) for all countries in the 2022 World Cup. This reflects the model's baseline ranking of each squad.
- [visualization2.png](./visualization2.png) – Pie chart showing the relative performance of countries during the group stage, based on points earned and advancement rates. Highlights the most dominant teams early in the tournament.
- [visualization3.png](./visualization3.png) – World map showing countries that reached the knockout stages, color-coded by how far they progressed (e.g., round of 16, quarterfinals, semifinals, final).
- [README.md](./README.md) – Project overview and documentation.


## Methodology

Each player is rated based on their position and relevant features (e.g. goals, assists, saves). Teams are then compared position-by-position to determine which has the statistical advantage.

The algorithm:
1. Assigns role-specific weights to player stats.
2. Aggregates positional matchups to simulate head-to-head games.
3. Predicts progression through the tournament bracket.

## Results

Our model successfully predicted that France would reach the finals, aligning closely with the actual outcome of the 2022 FIFA World Cup. While not based on machine learning, the system offers an interpretable, modular approach to game outcome forecasting.

## Tools & Technologies

- Python (Pandas, NumPy, Matplotlib)
- Jupyter Notebook
- Excel (for data cleaning and feature setup)


