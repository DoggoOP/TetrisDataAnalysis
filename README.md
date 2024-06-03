# Tetris Data Analysis

## Introduction
This project focuses on analyzing player performance data from Tetr.io, a competitive multiplayer version of the classic Tetris game. By examining various statistics, we aim to understand which factors most significantly influence player ratings and how different gameplay skills affect performance in various game modes.

## Features
- **Data Analysis:** Uses pandas for data manipulation and seaborn/matplotlib for visualization.
- **Performance Metrics:** Investigates the correlation between player ratings (Glicko) and key performance metrics such as APM (Attacks Per Minute), PPS (Pieces Placed Per Second), and VS (Versus score).
- **Skill Differentiation:** Analyzes how skills required for 40-line sprint and Blitz modes differ and affect player performance.
- **Improvement Insights:** Explores the relationship between the number of games played and improvements in player rating.

## Data Description
The dataset `tl-data-09-2023.csv` includes the following columns:
- `id`: Unique player identifier.
- `username`: Player's username.
- `gamesplayed`: Number of games played.
- `gameswon`: Number of games won.
- `tr`: Player's TR rating.
- `glicko`: Player's Glicko rating.
- `rd`: Rating deviation.
- `rank`: Player's rank.
- `bestrank`: Player's best rank.
- `apm`: Attacks per minute.
- `pps`: Pieces placed per second.
- `vs`: Versus score.
- `verified`: Verification status.
- `country`: Player's country.
- `40l_sprint`: 40-line sprint time.
- `blitz`: Blitz score.

## Analysis Summary
- **Correlation Analysis:** Strong correlations were found between Glicko rating and the metrics APM, PPS, and VS, with VS showing the highest correlation, indicating it is the most critical factor for improving player rating.
- **Skill Requirements:** Analysis of 40-line sprint and Blitz modes showed that PPS is the most influential metric for 40-line sprint times, while APM significantly impacts Blitz scores.
- **Improvement Through Practice:** The relationship between games played and Glicko rating suggests that while practice can lead to improvement, there is a skill ceiling influenced by individual spatial reasoning abilities.

## Visualizations
- Scatter plots and correlation coefficients to show relationships between Glicko rating and performance metrics.
- Visualization of the impact of PPS, APM, and VS on 40-line sprint and Blitz performance.
- Analysis of how the number of games played affects the Glicko rating over time.

## Getting Started
1. **Clone the repository:**
   ```bash
   git clone https://github.com/DoggoOP/TetrisDataAnalysis.git
   ```
2. **Install dependencies:**
   ```bash
   pip install pandas matplotlib seaborn numpy
   ```
3. **Run the analysis:**
   - Load the dataset and execute the analysis scripts to generate visualizations and insights.

## Conclusion
This project provides valuable insights into the factors that influence player performance in Tetr.io, highlighting the importance of certain skills and the impact of practice on player ratings.

---

Explore the detailed computational essay and visualizations to understand the intricacies of player performance in Tetr.io!
