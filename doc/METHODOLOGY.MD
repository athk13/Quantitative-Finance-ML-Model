# Methodology

## Data Preprocessing
Data preprocessing was a critical initial phase where we focused on cleaning and organizing our datasets. Specific steps included:
- Elimination of features with excessive missing data.
- Standardization to ensure comparability across various financial metrics.
- Imputation of missing values to maintain dataset integrity.

## Dimensionality Reduction
- Implemented PCA within distinct feature categories to reduce dimensionality and retain significant variance.

## Model Development
- Explored two machine learning models: Random Forest and XGBoost.
- Utilized a grid-search approach to optimize hyperparameters.

## Backtesting
- Conducted rigorous backtesting to evaluate the performance of investment strategies derived from model predictions.
- Metrics such as cumulative returns, Sharpe ratio, and maximum drawdown were analyzed.

For a detailed breakdown, see RESULTS.md.
