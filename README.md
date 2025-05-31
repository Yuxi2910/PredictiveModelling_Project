# PredictiveModelling_Project

# Forecasting Unemployment Insurance Claims in the US

## Overview
This repository contains a comprehensive modeling framework aimed at forecasting monthly Initial Claims (IC) and Continued Claims (CC) for unemployment insurance (UI) in the United States. It is a group project that utilized various predictive models and R language is used as the main tool. Accurate forecasting of UI claims is vital for informed policy-making, resource allocation, and labor market assessment.

## Objective
The primary goal is to evaluate and compare various statistical and machine learning methods to improve predictive accuracy by incorporating diverse economic, labor market, and financial indicators.

## Data
Data covers monthly observations from February 1971 to February 2024 and includes:

Target Variables:
- Initial Claims (IC)
- Continued Claims (CC)

Explanatory Variables:
- Labor Market Indicators: Unemployment level, job losers, discouraged workers
- Inflation Indicators: CPI, Core CPI, PCE, and PCE chain-type price index
- Income Indicators: Average hourly earnings
- Market Indicators: Consumer Sentiment Index, Brave-Butters-Kelley Real GDP estimate, Federal Funds Rate, NASDAQ Composite Index

## Modeling Approaches
Baseline Modeling: Ordinary Least Squares (OLS) with cross-validation

Regularization: Lasso and Ridge regression

Dimensionality Reduction: Principal Component Analysis (PCA)

Ensemble Learning: Gradient Boosting

Generalized Linear Models (GLMs): Gaussian identity link and Gamma log link

Time Series Modeling: ARIMA models

Random Forest

K-Nearest Neighbors (KNN)

## Key Findings
Boosting models achieved the best predictive accuracy.

GLM with Gamma-log link provided better model diagnostics and fit despite higher mean squared errors (MSE).

Regularization notably improved model robustness and prediction errors.

## Recommendations
Employ Gradient Boosting for high accuracy demands.

Choose GLM Gamma-log for interpretability and robustness.

Frequent retraining with updated economic data is advised.

Explore hybrid methods combining machine learning and time series approaches for enhanced predictive capability.

## Future Directions
Evaluate advanced normalization methods like Box-Cox transformations.

Develop models specifically tailored for predicting rare economic spikes and anomalies.

Incorporate regional and sector-specific variables for more granular predictions.

## Repository Structure
├── data/
│   └── [project_data]
├── models/
│   ├── ols & regularization & pca & boosting/
│   ├── glm/
│   ├── timeseries/
│   ├── knn & random_forest/
├── reports/
│   ├── final_report.pdf
│   └── project_presentation.pptx
└── README.md




