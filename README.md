# Quantitative-Finance-ML-Model
Advanced machine learning project for predicting CSI 800 stock returns, using PCA, Random Forest, and XGBoost models to identify orthogonal alphas and outperform market benchmarks in the Chinese stock market.

# Orthogonal Alphas Stock Prediction

This project was developed as part of an applied business project with Optimas Capital, focusing on predicting CSI 800 stock returns through advanced machine learning models, including Random Forest and XGBoost. Our goal was to build effective trading strategies by identifying orthogonal alphas in the Chinese stock market, leveraging large datasets encompassing over 2000 financial features.

## Project Overview

- **Objective**: To predict stock returns of the CSI 800 index using machine learning models and to identify orthogonal alphas for robust trading strategies.
- **Methodology**: Utilized data preprocessing techniques including Principal Component Analysis (PCA) for dimensionality reduction, followed by feature selection based on Information Coefficient (IC) scores. Developed predictive models using Random Forest and XGBoost, evaluated through backtesting to determine the most effective strategy.
- **Results**: Achieved orthogonal alphas with a correlation under 0.05, with strategies that outperformed the market benchmark by 17.81%.

## Repository Structure

- `/notebooks`: Jupyter notebooks demonstrating the data preprocessing, model training, and evaluation phases. *(Note: Direct data or sensitive information is excluded.)*
- `/src`: Source code for data preprocessing, model training, evaluation scripts, and utility functions. *(Data not included.)*
- `/doc`: Additional documentation, including project reports and analysis insights.

## Getting Started

Due to NDA restrictions, the dataset cannot be provided. However, the methodology described can be applied to similar datasets. Ensure your Python environment includes libraries such as scikit-learn, xgboost, pandas, numpy, and matplotlib for exploring the project.

## Key Findings

- **Data Preprocessing**: Critical in managing the large feature set, PCA helped in reducing dimensionality while retaining variability.
- **Model Comparison**: XGBoost outperformed Random Forest in terms of the strategy alpha, generating a higher return on the top-layer stocks.
- **Strategy Evaluation**: Our backtesting results demonstrate the effectiveness of the predictive models, with particular strategies significantly outperforming the CSI 300 benchmark.

## Conclusion

This project showcases the potential of machine learning in quantitative finance, especially in the context of the Chinese stock market. Our approach, from rigorous data preprocessing to strategic model application, underscores the importance of sophisticated algorithms in identifying profitable trading opportunities.
