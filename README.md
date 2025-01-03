# Promotion Price Sensitivity Analysis for N Brown

This repository contains the **report** and **presentation** for the team-based industry project conducted in collaboration with N Brown, a leading UK retailer. The project focuses on analyzing **price elasticity of demand (PED)** and forecasting sales using advanced statistical and machine learning techniques to support strategic pricing and sales predictions.

## Project Overview

In the competitive retail landscape, understanding consumer sensitivity to price changes is critical. This project addresses the following key objectives:
1. **Price Elasticity Analysis**: Determine how price changes impact consumer demand using **Ordinary Least Squares (OLS)** regression.
2. **Sales Forecasting**: Predict future sales volumes under different scenarios using **ARIMA**, **SARIMA**, and **Prophet** models.
3. **Seasonality Analysis**: Identify and incorporate seasonal trends into the forecasting models for more accurate predictions.

### Key Insights:
- **Price Elasticity**: Products in department 0 exhibited low sensitivity to price changes (mean PED: 0.20), with the majority being price inelastic (99%).
- **Forecasting**: SARIMA models accurately captured seasonal patterns, predicting daily order volumes with a Mean Absolute Error (MAE) of 5,666 for December 2018.
- **Seasonality**: Discount-driven spikes were observed during October, necessitating seasonal adjustments in forecasting models.

## Repository Contents

- **SCC460 Kappa Report.pdf**: Detailed report covering methodology, results, and conclusions.
- **PPT Team Kappa.pdf**: Presentation summarizing key findings and methodologies used.

## Methodology

### 1. Preprocessing:
- Cleaned and formatted data for analysis (e.g., handling missing values, converting date formats).
- Removed sparse and inconsistent data (e.g., 2019 data due to irregular entries).

### 2. Exploratory Data Analysis:
- Investigated chronological and seasonal trends in order volumes.
- Focused analysis on department 0, the largest contributor to order volumes.

### 3. Modeling Approaches:
- **OLS Regression**: Quantified the relationship between discounts and sales.
- **ARIMA and SARIMA**: Captured time series trends and seasonal patterns.
- **Prophet**: Modeled non-linear trends and holiday effects.

### 4. Results:
- SARIMA was identified as the best-performing model based on AIC as compared to ARIMA.
- Elasticity analysis revealed opportunities for price adjustments to enhance profitability.

## Team Contributions

This was a collaborative project led by **Team Kappa**:
- **Akash Marar**: Department analysis, seasonality insights, and exploratory data analysis.
- **Donald (Tze Thoe)**: Price elasticity findings and exploratory analysis.
- **Anam Khan**: Regression and OLS modeling.
- **Pratamesh Takale**: ARIMA and SARIMA modeling.
- **Ben Grime & Zeerak Khan**: Presentation and report collation.

## Future Work

- Investigate elasticity across all departments for broader insights.
- Enhance forecasting models by incorporating additional years of data.
- Refine seasonal adjustments and cross-validate models for improved accuracy.

## How to Use

This repository serves as a reference for implementing price sensitivity and forecasting models in retail. The **report** provides a detailed breakdown of the methodology, while the **presentation** offers a concise overview of key findings.

## License

This project is proprietary and developed for academic and industry collaboration purposes.

## Acknowledgements

This project was completed as part of the SCC-460 module at Lancaster University in collaboration with N Brown.
