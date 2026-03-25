# ⚽ Statistical Analytics of FIFA Players using Python
--------------------
## 📌 Project Overview

This project performs a statistical data analysis of FIFA player attributes using Python. The dataset contains 18,207 football players with 88 attributes, including demographic information, performance ratings, financial data, and physical characteristics.

The goal of this project is to apply statistical techniques and data analysis methods to understand player performance, detect anomalies in wages, explore relationships between skills and overall ratings, and analyze demographic trends across different player positions.

Using Python, Pandas, NumPy, Matplotlib, Seaborn, and SciPy, this project demonstrates how statistical methods can uncover insights useful for football scouts, club managers, analysts, and game developers.

---------------
## 🎯 Project Objectives
* Perform data inspection and cleaning to ensure data quality.
* Identify outliers in player wages using statistical techniques.
* Analyze statistical distributions of player attributes.
* Study the relationship between skills and overall player ratings.
* Perform ANOVA tests to examine differences in physical attributes across positions.
* Demonstrate the Central Limit Theorem (CLT) using player potential scores.

-------------
## 📊 Dataset Information

* **Dataset Name**: FIFA Player Dataset `(Game.xlsx)`
* **Total Records**: 18,207 players
* **Total Features**: 88 attributes

## Important Columns
* **ID** – Unique player identifier
* **Name** – Player name
* **Age** – Player age
* **Nationality** – Country of origin
* **Overall** – Current performance rating
* **Potential** – Future performance potential
* **Club** – Player's current club
* **Wage** – Weekly salary (€)
* **Weight** – Player weight
* **Height** – Player height
* **Position** – Playing position (ST, GK, CM, etc.)
* **Skill Attributes** – Passing, Dribbling, Finishing, etc.
------------------------
## ⚙️ Steps Taken
### Data Inspection
* Loaded dataset using **Pandas**
* Checked dataset shape **(18,207 × 88)**
* Inspected missing values and data types
### Data Cleaning
* Handled missing values
* Standardized wage and value columns
* Prepared variables for statistical analysis
### Outlier Detection
* Applied Interquartile Range (IQR) method
* Detected extreme wage values
### Distribution Analysis
* Analyzed Potential distribution
* Compared Normal distribution vs Student’s t-distribution
### Correlation Analysis
* Studied relationships between skill attributes and player ratings
### Statistical Testing
* Applied ANOVA tests on physical attributes by position
### Central Limit Theorem Demonstration
* Sample means of Potential were analyzed to validate CLT
-------------------

## 🛠️ Technologies Used
* **Python**
* **Pandas** – Data Cleaning & Manipulation
* **NumPy** – Numerical Calculations
* **Matplotlib** – Data Visualization
* **Seaborn** – Statistical Visualization
* **SciPy** – Statistical Distributions
* **Jupyter Notebook**
---------------------

## 📈 Key Analyses Performed
* Dataset inspection and cleaning
* Outlier detection in Wage column using IQR
* Distribution analysis of Potential
* Comparison of Normal vs Student’s t-distribution
* Correlation analysis of player skills with Overall and Potential ratings
* ANOVA tests on Height and Weight across player positions
* Central Limit Theorem demonstration using sample means
---------------------------

## 🔍 Key Insights
* Elite players such as Lionel Messi and Cristiano Ronaldo appear as wage outliers, reflecting the extreme salary differences between star players and the rest of the player population.
* The Potential rating distribution is approximately normal, with most players falling within the 65–85 range, indicating a balanced distribution of player potential.
* ShortPassing shows the strongest correlation (~0.50) with Overall and Potential ratings, suggesting that passing ability plays a major role in overall player performance.
* Other important skills influencing player ratings include:
  * Dribbling
  * Finishing
  * Long Passing
* ANOVA results show significant differences in Height and Weight across positions, confirming that physical attributes vary depending on player roles.
* The Central Limit Theorem was validated, showing that the distribution of sample means of Potential becomes approximately normal when sample size ≥ 30.
* Student’s t-distribution better captures extreme values compared to the normal distribution, making it useful when working with smaller samples.
----------------

## 📊 Conclusion
This statistical analysis of FIFA player data highlights important relationships between player skills, physical attributes, and economic valuation. The results show that elite players significantly influence wage distributions, while core skills such as passing, dribbling, and finishing strongly impact overall performance ratings.

Additionally, statistical tests confirm that physical characteristics vary across playing positions, supporting the idea that recruitment strategies should consider both technical and physical attributes.

These findings demonstrate how statistical analytics can provide valuable insights for football analytics, talent scouting, and player valuation models.
