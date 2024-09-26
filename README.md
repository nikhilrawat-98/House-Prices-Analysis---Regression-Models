# House Prices Analysis - Regression Models

This project focuses on analyzing house prices using multiple linear regression models. The goal is to identify the best predictors of house prices based on various factors such as lot size, number of bedrooms, bathrooms, and other features. The analysis was conducted using data from Windsor, Canada, containing information on house sales during July-September 1987.

## Project Overview

- **Regression Analysis**: The analysis uses multiple linear regression to model the relationship between house prices (dependent variable) and a set of predictor variables such as lot size, bedrooms, bathrooms, and more.
- **Model Justification**: Multiple linear regression is chosen to identify the relationship between house prices and various predictors, allowing us to understand how different features impact the price.
- **Tech Stack**: Python, Pandas, Scikit-learn, Matplotlib, Statsmodels

## Dataset

The dataset contains information on 546 house sales in Windsor, Canada, during July-September 1987. The dataset includes variables like lot size, bedrooms, bathrooms, and several other features that are important when considering house prices.

### Dataset Citation:
> Data Source: [House Prices Dataset](http://qed.econ.queensu.ca/jae/1996-v11.6/anglin-gencay/)

## File Structure
- **`House Prices Analysis- Regression Models.pdf`**: Detailed report discussing the methodology, regression models, and results.

## Model and Performance

The multiple linear regression model was trained and evaluated, achieving:
- **Adjusted R-Squared**: 0.64, indicating the proportion of the variance in house prices that is predictable from the selected predictors.
- **Significance of Predictors**: Most predictors such as lot size, bathrooms, and stories have significant relationships with house prices (P-value < 0.05).
- **Exclusion of Full Base**: After multicollinearity analysis, the full base variable was excluded to improve model performance, while maintaining high significance for other predictors.

## Usage

The Jupyter notebook demonstrates the following:
1. Loading and preprocessing the dataset.
2. Performing exploratory data analysis (EDA).
3. Training multiple linear regression models.
4. Evaluating the model performance using metrics such as R-squared and P-values.

## Acknowledgements

The project was developed as part of an MSc course in Business Analytics.

## License

MIT License
