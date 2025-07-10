# NBA Top Performer Prediction

This project explores what attributes contribute to top NBA performance using a combination of data cleaning, feature engineering, and predictive modeling in Python.

## About the Project
Using a dataset of NBA players since 1996, I created a classification model to predict whether a player will become a top performer based on attributes like height, weight, college attended, and rookie age.

I also conducted visual analysis in Tableau to explore player trends and support my model's findings.

## Data Manipulation
To conduct a focused and career level analysis, I transformed the raw data into three cleaned and purpose driven datasets:

### Career-Wide Dataset (nba_career4.csv)
This dataset consolidates each player’s season level data into a single row per player, capturing their overall career averages and totals. This version is used primarily for exploring overall trend.
- Only players whose rookie season was 1996 or later were included to ensure complete career data is available through 2023.
- Duplicate and erroneous entries were not present in the original dataset.

### Rookie and Final Year Dataset (nba_rookie_final.csv)
This dataset records each player’s rookie season and final season stats, enabling comparisons between how players started and how their careers ended. It was useful in assessing early indicators of long term performance.
- Players whose rookie year was before 1996 were excluded due to missing rookie year stats.

### Top Performer Dataset (top_performers.csv)
This dataset builds on the career-wide data and includes engineered features like stat ranges and count of performance criteria met. Each player is labeled as a “top performer” or not, based on how many performance thresholds they met. This version was used to train and test the predictive model.

## Tools & Libraries
- Python (pandas, NumPy, scikit-learn)
- Jupyter Notebook
- Tableau (linked in portfolio)

## Key Highlights
- Cleaned and processed real-world basketball data
- Engineered features from multiple datasets (career stats + rookie data + top performance)
- Built and evaluated predictive models (Random Forest)
- Balanced the dataset and tuned thresholds for improved accuracy
- Interpreted results for use by NBA scouts and analysts

## Portfolio & Project Overview
You can view the full project summary and Tableau visualizations here:  

