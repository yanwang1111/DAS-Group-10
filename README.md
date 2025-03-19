# Movie Dataset Analysis

## Project Overview
This repository contains an analysis of a movie dataset using R and Quarto. The analysis explores trends in movie ratings, genres, and yearly movie counts. It also includes regression modeling to identify key factors influencing movie ratings.

## Features
- **Data Cleaning**: Removing missing values to ensure data integrity.
- **Exploratory Data Analysis (EDA)**: Visualizing the distribution of ratings, the most common movie genres, and the number of movies released per year.
- **Binary Classification**: Transforming ratings into binary categories to predict high vs. low-rated movies.
- **Regression Modeling**: 
  - Linear regression to analyze continuous rating predictions.
  - Logistic regression to classify movies into high/low ratings.
  - Model selection based on AIC values.
- **Visualization**: Graphical representations of rating distributions, genre trends, and model predictions.

## Repository Contents
- `movie_analysis.qmd`: Quarto file containing the full analysis, including data processing, visualization, and modeling.
- `dataset10.csv`: The dataset used for analysis (if applicable, otherwise link to source).
- `README.md`: Overview of the project.

## Model Selection Conclusion
Based on model comparison, the logistic regression model without the `year` variable was selected, as it had the lowest AIC value. The analysis also showed that both `year` and the movie identifier were statistically insignificant (p-value > 0.05), so they were removed to maintain a simpler and more efficient model.

## Contact
For any questions or collaboration, feel free to reach out or submit a pull request!

---
_This project is created as part of an academic/statistical analysis exercise._
