# Results and Performance Analysis

## Executive Summary
The project utilized machine learning algorithms to analyze and predict the stock returns for CSI 800, focusing on generating orthogonal alphas. The final evaluation of strategies indicates a significant outperformance against the benchmark index.

## Detailed Performance Metrics

### Random Forest Model
- **Alpha**:
  - Standardized Features: 0.06
  - PCA 5 Components: 0.13
  - PCA 10 Components: 0.04
- **Correlation Coefficient with asig-fsig strategy**:
  - Standardized data: 0.072
  - PCA 5 components: -0.045 (indicating low similarity and higher orthogonality)
  - PCA 10 components: -0.03

### XGBoost Model
- The **strategy alpha** varied depending on the feature set used:
  - PCA 5 with IC > 0.03: Alpha of 17.81%
  - PCA 5 with IC > 0.05: Alpha of 17.36%
  - PCA 10 with IC > 0.03: Alpha of 14.22%
  - Standardized features with IC > 0.03: Alpha of 11.78%

### Strategy Performance Comparison
- **PCA 5 (IC > 0.03)**:
  - Cumulative Return: 490.72%
  - Average Annual Return: 17.37%
  - Sharpe Ratio: 0.71
  - Max Drawdown: -33.26%
  - Volatility (annual): 21.15%

### Long-Short Strategy Backtesting
- Compared with CSI 300/CSI 500/ FTSE A50/HSCEI index, the long-short strategy showed significant alpha generation with different feature sets.
- Correlation with asig-fsig strategy showed a coefficient of -0.09594, suggesting low similarity and potential for diversification.

### Model and Strategy Comparison
- **Random Forest vs. XGBoost**:
  - XGBoost achieved a higher strategy average annual return of 10.7% compared to Random Forest's 9.43%.
  - XGBoost had a higher alpha of 17.81% compared to Random Forest's 13%.

### Conclusion
The comprehensive analysis showed that the XGBoost model, especially when using PCA with 5 components and an IC > 0.03, provided the best performance in terms of both alpha generation and risk-adjusted return. The PCA datasets consistently outperformed the standardized datasets, suggesting that dimensionality reduction played a key role in the models' success.

---

The results presented in this document are extracted from the final slides of the provided PDF presentation. They represent the key metrics and findings from the applied business project conducted in collaboration with UCLA and Optimas. These results underscore the efficacy of using machine learning techniques in quantitative finance to create robust trading strategies.
