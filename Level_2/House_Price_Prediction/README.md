# Level 2 — Task 1: House Price Prediction

## Project Overview

This project focuses on predicting house prices using machine learning techniques.

The project includes data exploration, data cleaning, preprocessing, feature encoding, model training, and evaluation.

## Dataset

The dataset contains 1,460 house records with 81 features before preprocessing.

## Data Preprocessing

The following steps were performed:

- Missing value analysis
- Duplicate checking
- Missing value handling
- Categorical feature encoding
- Numerical feature preparation
- Train-test splitting

After preprocessing:

- Training features: 1,168
- Testing features: 292
- Total processed features: 245

## Model Evaluation

The model was evaluated using:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

### Results

- MSE: 1.019680e+09
- RMSE: 31,932.44
- R² Score: 0.8671

The R² score indicates that the model explains approximately 86.7% of the variance in house prices on the test data.

## Feature Importance

Important features were analyzed using model coefficients.

Some of the features with larger absolute coefficients included:

- PoolQC_Gd
- Condition2_PosN
- PoolQC_Fa
- Condition2_PosA
- Functional_Sev
- RoofMatl_WdShngl
- Condition2_RRAe
- RoofStyle_Gable
- RoofStyle_Hip
- Heating_Wall

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Files

- `Task1_House_Price.ipynb`
- `README.md`

## Conclusion

This project demonstrates the complete machine learning workflow for house price prediction, including data preprocessing, categorical encoding, model training, feature analysis, and model evaluation.

The model achieved an R² score of approximately 0.867, demonstrating a strong predictive relationship between the processed features and house prices.
