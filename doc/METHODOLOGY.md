# Methodology

## Data Preprocessing
The project processed a dataset consisting of 2043 features, implementing steps such as:
- Removal of features with more than 70% missing data.
- Standardization to neutralize scale effects.
- Missing value imputation with feature averages.

## Dimensionality Reduction
- Employed PCA within defined categories, reducing feature dimensions while preserving essential information (e.g., PCA with 5 components vs. 10 components).

## Datasets Utilized
The project harnessed three types of datasets after an initial preprocessing phase:
- **Standardized Features Dataset**: The raw data were standardized across all features to normalize the range and scale, facilitating a fair comparison and ensuring that each feature contributes proportionately to the final model.
- **PCA 5 Components Dataset**: To manage the high-dimensionality, Principal Component Analysis (PCA) was applied to reduce each category of features into five principal components. This transformation aimed to capture the most significant variance within the data while minimizing information loss.
- **PCA 10 Components Dataset**: A more detailed PCA, retaining ten principal components from each feature category to provide a richer representation of the underlying data structures and potential relationships.

## Model Testing and Evaluation
Each dataset underwent a rigorous analysis through two main machine learning models:

### Random Forest
- Built on decision tree ensembles, this model offered insights into feature importance and model interpretability. Its performance was gauged on its ability to reduce overfitting while maintaining accuracy.

### XGBoost
- Recognized for its efficiency and performance, the XGBoost model was pivotal in navigating the datasets' complexity and identifying key predictive signals within the stocks' historical data.

## Comparative Analysis
The models were tested across all three datasets to:
- Assess the impact of data preprocessing methods on model performance.
- Determine the optimal level of dimensionality reduction.
- Establish a robust strategy that could withstand market fluctuations and predict future returns with higher confidence.

## Backtesting
- The strategy backtesting showed a cumulative return of 606.24% for the top-layer stocks using PCA 5 components, substantially surpassing the benchmark's performance.
- Strategies demonstrated robustness with a Sharpe ratio reaching up to 0.73, indicating a favourable risk-adjusted return.

For detailed analysis of results, refer to RESULTS.md.

