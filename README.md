# California Housing Price Prediction

## Project Overview
This project predicts median house values using the California Housing dataset and compares three regression algorithms: Ordinary Least Squares (OLS), Ridge Regression, and Lasso Regression.

## Objectives
- Explore and analyze the housing dataset.
- Handle missing values using median imputation.
- Engineer interaction and ratio features.
- Encode categorical variables and standardize numerical features.
- Investigate multicollinearity using correlation analysis and VIF.
- Tune Ridge and Lasso hyperparameters using GridSearchCV.
- Evaluate models using RMSE, MAE, and R².
- Visualize predictions and residual distributions.

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

## Files
- `California_Housing_Regression.ipynb` — complete analysis, model training, evaluation, and visualizations.
- `housing.txt` — dataset file used by the notebook.

## Results
The initial model comparison produced the following test-set results:

| Model | RMSE | MAE | R² |
|---|---:|---:|---:|
| OLS | 69048.19 | 49376.49 | 0.6362 |
| Ridge | 69056.22 | 49382.63 | 0.6361 |
| Lasso | 69100.07 | 49369.60 | 0.6356 |

OLS achieved the lowest test RMSE in this experiment. Lasso achieved the lowest test MAE. The models performed similarly overall.

## How to Run
1. Download or clone this repository.
2. Open `California_Housing_Regression.ipynb` in Google Colab or Jupyter Notebook.
3. Ensure `housing.txt` is available in the expected dataset path.
4. Run the notebook cells in order.

## Conclusion
This project demonstrates data preprocessing, feature engineering, multicollinearity analysis, regression model comparison, hyperparameter tuning, and residual diagnostics.
