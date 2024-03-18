# Methodology

## Data Preprocessing
The project processed a dataset consisting of 2043 features, implementing steps such as:
- Removal of features with more than 70% missing data.
- Standardization to neutralize scale effects.
- Missing value imputation with feature averages.

## Dimensionality Reduction
- Employed PCA within defined categories, reducing feature dimensions while preserving essential information (e.g., PCA with 5 components vs. 10 components).

## Model Development
- Applied Random Forest and XGBoost models, fine-tuning parameters using techniques like RandomizedSearchCV for optimal performance.
- Feature selection was guided by the mean absolute IC score, with a threshold of >0.05 to ensure relevance.

## Backtesting
- The strategy backtesting showed a cumulative return of 606.24% for the top-layer stocks using PCA 5 components, substantially surpassing the benchmark's performance.
- Strategies demonstrated robustness with a Sharpe ratio reaching up to 0.73, indicating a favourable risk-adjusted return.

For detailed analysis of results, refer to RESULTS.md.

