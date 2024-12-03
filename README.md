# ATP Tennis Data Analysis for Broadcasters and Sponsors

## Overview

This project analyzes ATP tennis matches from 2001 to 2023, exploring trends, patterns, and key insights in the sport. By leveraging data analysis, machine learning, and visualization techniques, it provides actionable insights for various stakeholders such as sports broadcasters, betting companies, and brand sponsors.

---

## Goals and Key Analyses

1. **Performance on Different Surfaces**:
   - Analyzes top players' performance (e.g., Rafael Nadal, Roger Federer) on clay, grass, and hard courts.
   - Examines win rates and performance factors such as court type, player attributes, and match data.

2. **Impact of Player Age on Performance**:
   - Evaluates how age affects game stamina, match duration, and outcomes.
   - Provides actionable insights for broadcasters to predict match lengths for scheduling purposes.

3. **Clash of Legends**:
   - Studies outcomes of legendary matchups (e.g., Djokovic vs. Nadal) and identifies factors contributing to wins, such as court type, player age, and playing hand.

4. **Impact of Aces on Match Outcomes**:
   - Investigates whether a higher number of aces correlates with match wins.
   - Offers insights for betting strategies and sports commentary.

5. **Winner Prediction Using Machine Learning**:
   - Builds a Random Forest Classifier to predict match winners based on player statistics, court type, and other features.

---

## Data Processing and Methodology

- **Data Cleaning**:
  - Removed irrelevant columns (e.g., high NaN values, non-impactful data).
  - Imputed missing values where necessary.

- **Feature Engineering**:
  - Created meaningful features such as win rates by surface, ace counts, and break-point statistics.
  - One-hot encoded categorical variables (e.g., surface type).

- **Machine Learning**:
  - Used a `RandomForestClassifier` for winner prediction.
  - Split data into training and testing sets for robust evaluation.

---

## Key Findings

1. **Court-Type Performance**:
   - Nadal dominates on clay with a win rate of 97%.
   - Federer shows consistent excellence on grass.

2. **Impact of Age**:
   - Younger players tend to have longer matches, suggesting stamina-related effects.

3. **Aces and Winning**:
   - Aces are strongly correlated with winning matches, making them a key predictor.

4. **Branding Opportunities**:
   - Brands should align sponsorships with players' geographical and surface-specific strengths.

---

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/paithanemehul/Tennis-Through-the-Decades.git
   cd Tennis-Through-the-Decades
