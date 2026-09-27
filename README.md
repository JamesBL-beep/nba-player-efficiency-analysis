NBA Player Efficiency Analysis

Overview

This project analyzes NBA player statistics using Python to investigate the relationship between minutes played and player efficiency per minute.

The analysis examines whether minutes played are associated with efficiency and explores whether other player statistics provide additional explanatory value.

Research Question

How does minutes played relate to NBA player efficiency per minute, and how does this relationship change when other player statistics are considered?

Objectives

Clean and prepare NBA player statistics for analysis.

Calculate an efficiency-per-minute metric.

Examine the relationship between minutes played and efficiency.

Investigate the effect of low-minute observations on the results.

Build a multiple linear regression model using additional player statistics.

Evaluate model performance using R² and Mean Absolute Error (MAE).

Compare training and test performance to check for potential overfitting.

Data

The project uses player-level NBA statistics stored in CSV format.

Variables used include:

MP — Minutes played per game

PTS — Points per game

TRB — Total rebounds per game

AST — Assists per game

STL — Steals per game

BLK — Blocks per game

TOV — Turnovers per game

Pos — Player position, when available

Methods

The analysis uses:

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Pearson correlation

Multiple linear regression

R²

Mean Absolute Error (MAE)

Low-minute observations are examined separately to investigate their potential influence on the relationship between minutes played and efficiency.

Regression Model

The regression model uses available player statistics as features to predict EFF_per_min.

The dataset is divided into training and test sets. The training set is used to fit the model, while the test set is used to evaluate how well the model performs on unseen data.

Results

The project includes:

Correlation analysis between minutes played and efficiency per minute

Scatter-plot visualizations

Regression coefficients

R² and MAE model evaluation

Training vs. test performance comparison

Analysis of low-minute observations

The numerical results can be found in the project output files.

Project Structure

nba-player-efficiency-analysis/
│
├── README.md
├── nba_efficiency_analysis.ipynb
├── data/
│   └── player_stats.csv
├── results/
│   ├── project_results.xlsx
│   └── figures/
│       └── mp_vs_efficiency.png
└── requirements.txt

How to Run

The analysis was developed using Google Colab.

Open nba_efficiency_analysis.ipynb.

Upload the required CSV dataset.

Run the notebook cells in order.

The analysis will generate the cleaned dataset, statistical results, regression results, and visualizations.

Author

James
