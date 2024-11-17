# Regression Analysis: Housing Prices Prediction
This project combines two key regression tasks related to housing price prediction. It demonstrates the process of building and evaluating machine learning models for predictive analysis using real-world-inspired datasets.

## Project Overview

### 1. Predicting California Housing Prices
This task focused on predicting `median_house_value` using data provided in the file `housing.csv`. Each data point represents features of a specific area in California.

**Key observations:**

- `median_house_value` is correlated with features such as `median_income`, `longitude`, and `latitude`.
- A regression model was built to estimate `median_house_value` based on these and other features.

**Motivation:**

- This project was inspired by the Zillow Kaggle Prize, which featured a $1,200,000 prize pool.
- By simulating a similar problem, I aimed to explore housing market prediction in a real-world context.

### 2. Predicting `SalePrice` Using Nonlinear Regression Models
The second task involved predicting `SalePrice` using nonlinear regression models. 

**Key objectives:**

- Build and tune models (KNN, Random Forest, XGBoost).
- Optimize hyperparameters using cross-validation to minimize MAPE.
- Evaluate model performance using various metrics.

## Evaluation
After selecting the best hyperparameters, models were trained on the full training set and evaluated on the testing set. Metrics included:

- **Mean Squared Error (MSE)**
- **Mean Absolute Error (MAE)**
- **Mean Absolute Percentage Error (MAPE)**

## Key Visualizations
- Hyperparameter vs. MAPE curve to analyze the impact of tuning.
- Scatter plots for predicted vs. actual values:
  - `Y_train` vs. `Y_train_pred`.
  - `Y_test` vs. `Y_test_pred`.
- Regional visualization of predictions on maps (for Task 1).

## Next Steps:
- Explore additional hyperparameters for Random Forest and XGBoost.
- Incorporate feature selection to improve interpretability.
- Extend analysis to other datasets for broader applicability.

## Contact Information
Feel free to reach out with questions or suggestions:

- **Name**: Akbar Shah
- **Email**: [akbarshah908@outlook.com](mailto:akbarshah908@outlook.com)

Thank you for exploring this project!
