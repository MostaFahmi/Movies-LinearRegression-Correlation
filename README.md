# Movies Dataset Analysis
## Overview
This project focuses on exploring and analyzing a dataset containing information about movies, including details such as ratings, genres, release years, budgets, gross earnings, and more. The main goal is to uncover patterns, correlations, and insights within the data, with a particular emphasis on the financial aspects of the movies.

## Data Cleaning and Preprocessing
The initial dataset contained missing values, particularly in the 'rating', 'budget', and 'gross' columns.
Columns with less than or equal to 5% missing values were retained, while others were dropped.
For the 'budget' column (with more than 5% missing values), missing values were filled using the median budget for each respective year.
Data types were adjusted, and duplicate entries were removed.
## Exploratory Data Analysis (EDA)
Outliers were identified and analyzed to understand their impact on the dataset.
Correlations between different variables were visualized using a heatmap and pairplot.
Strong positive correlations were found between 'gross' and 'budget', as well as a moderate correlation between 'gross' and 'votes'.
Company Names Standardization
Movie production companies with fewer than 10 movies were excluded from the analysis.
Similar company names were grouped to provide a more concise and meaningful representation.
## Regression Modeling
A new column, 'pct_revenues', was created to represent the percentage of revenue generated compared to the budget.
The incremental year column, 'year_incremental', was introduced to facilitate the analysis of revenue trends over the years.
Linear regression models were built to explore the relationships between different variables. A model predicting 'gross' based on 'budget' showed a reasonable fit (R-squared value of 0.55).
## Conclusion
The analysis provides insights into the factors influencing movie revenues, with a strong positive correlation between budget and gross earnings.
The dataset has been cleaned and processed for further analysis, and a regression model has been developed to predict gross earnings based on budget.
## Future Steps
Further exploration could involve more advanced modeling techniques, feature engineering, and a deeper understanding of the movie industry trends.
Additional external datasets could be incorporated to enhance the analysis.
Visualization and interpretation of the regression model results could be expanded for a more comprehensive understanding.
