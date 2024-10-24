## Overview
This repository contains analyses performed for a data analysis assignment that focuses on two primary topics: estimating real estate property values and analyzing the impact of packaging type and storage conditions on product freshness. The analyses leverage statistical methods to draw insights from the provided datasets.

## Question 1: Real Estate Analysis
A real estate company aims to estimate the value of properties in a stable market using data collected from 197 property sales. The analysis involves:

### Key Tasks
- **Data Visualization**: 
  - Produce plots and a correlation matrix to explore relationships between property price (response variable) and predictors such as size, age, and number of bedrooms.
  
- **Model Fitting**: 
  - Fit a multiple regression model using all predictors to explain property prices and estimate the impact of property size on prices through confidence intervals.

- **Model Evaluation**: 
  - Conduct an ANOVA test to assess the significance of the predictors and check the assumptions of the regression model, including homoscedasticity and normality of residuals.

- **Model Selection**: 
  - Utilize regression analysis to identify the best model, potentially removing non-significant predictors.

## Question 2: Consumer Goods Analysis
This part of the assignment focuses on how packaging type and storage conditions affect product freshness. The analysis includes:

### Key Tasks
- **Study Design Evaluation**: 
  - Determine if the design is balanced or unbalanced based on the number of replicates across packaging and storage combinations.

- **Data Visualization**: 
  - Construct boxplots and interaction plots to investigate the effects of packaging and storage on freshness scores.

- **Mathematical Modeling**: 
  - Formulate a full interaction model to analyze the effects of packaging type and storage conditions on product freshness.

- **Statistical Analysis**: 
  - Perform regression and ANOVA analyses to evaluate the significance of main effects and interaction terms, while checking model assumptions.

## Datasets
- `realestate2024.csv`: Contains data on property sales including price, size, age, and number of bedrooms.
- `goods.csv`: Includes data on product freshness related to different packaging types and storage conditions.

## Installation
1. Clone this repository to your local machine.
2. Ensure that you have R and the necessary packages (e.g., `knitr`, `ggplot2`, etc.) installed.
3. Run the R scripts to reproduce the analyses.

## License
This project is licensed under the MIT License. Feel free to use, modify, and distribute this analysis as needed.

## Contact
For any questions or feedback regarding this assignment, please contact Thuy Vy (Sylvia Tran) at sylviatran151@gmail.com.
