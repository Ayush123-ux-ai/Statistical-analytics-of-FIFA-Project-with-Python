# Statistical-analytics-of-FIFA-Project-with-Python

## Project Overview

The FIFA Player Dataset ("Game.xlsx") provides a comprehensive collection of attributes for football players, including demographic details (e.g., Age, Nationality), performance metrics (e.g., Overall, Potential), financial data (e.g., Wage, Value), and physical characteristics (e.g., Weight, Height). This dataset, sourced from a football simulation game, offers a rich opportunity to apply advanced statistical techniques to uncover insights about player profiles, performance potential, and economic valuation. The objective of this project is to perform an end-to-end data analytics study using Python and Pandas, focusing on statistical methods to analyze distributions, detect anomalies, estimate population parameters, and validate statistical theorems. The project aims to provide actionable insights for stakeholders such as football scouts, team managers, and game developers by exploring relationships between player attributes and their market value, demographic trends, and performance distributions.4

## Key Analyses Performed

Data inspection and cleaning (shape: 18,207×88, null value handling)

Outlier detection in Wages using IQR method (top: L. Messi, L. Suaez)

Statistical distributions (Normal vs t-distribution, Standard Normal on Potential)

Correlation matrix of skills with Overall/Potential ratings

ANOVA tests on physical attributes (Height, Weight) by Position

Central Limit Theorem demonstration via sample means of Potential

## Dataset Details

The dataset contains 18,207 records (rows) and multiple columns, including but not limited to:

ID: Unique player identifier

Name: Player name

Age: Player age

Nationality: Player's country of origin

Overall: Current performance rating

Potential: Potential performance rating

Club: Current club

Wage: Weekly wage (in €, with 'K' or 'M' suffixes)

Weight: Player weight (in lbs)

Position: Player's field position (e.g., ST, GK, CM)

Additional Attributes: Skills (e.g., Dribbling, Passing), physical metrics, and contract details

## Libraries Used

Pandas for data processing

NumPy for calculations

Matplotlib and Seaborn for visualizations

SciPy.stats for distributions

## How to Run this Project

Clone the GitHub repository containing stastical-analysis-FIFA.ipynb

Place the DGame.xlsx dataset (18,207 players, 88 columns) in the same directory​

Launch Jupyter: jupyter notebook​

Open stastical-analysis-FIFA.ipynb and run all cells sequentially


## Key Insights

The FIFA player data analysis across 18,207 players and 88 attributes reveals L.Messi,L.Suarez,L.Modric,Cristiano Ronaldo , and Luka Modrić as extreme outliers detected via IQR method, highlighting massive valuation disparities. ShortPassing shows the strongest correlation (0.50) with Overall/Potential ratings, alongside Dribbling, Finishing, and LongPassing, underscoring playmaking skills as key performance predictors. ANOVA confirms significant Height/Weight differences by position (p=0.0), supporting targeted recruitment, while Central Limit Theorem validation demonstrates sample means of Potential normalize for n≥30, and distributions fit Normal centrally but t-distribution better captures extremes.







