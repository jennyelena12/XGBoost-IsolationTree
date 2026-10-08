# Analisis Dampak Energi Ramah Lingkungan pada Bangunan terhadap Kualitas Udara

## Overview

This research investigates the impact of renewable energy usage in buildings on air quality using machine learning techniques. The study applies the CRISP-DM framework and compares several predictive models, including Random Forest, XGBoost, and Stacking models optimized with Bayesian Optimization. The objective is to identify the relationship between renewable energy adoption and air quality improvement.

## Key Contributions

* Analyzed the relationship between renewable energy usage and air quality indicators.
* Developed predictive models using Random Forest, XGBoost, and Stacking approaches.
* Applied Bayesian Optimization for hyperparameter tuning.
* Identified a strong negative correlation between renewable energy percentage and Air Quality Index (AQI).
* Achieved the best performance using a Stacking model (Random Forest + XGBoost) with Lasso Regression as the meta-model.

## Methodology

* Framework: CRISP-DM
* Models:

  * Random Forest
  * XGBoost
  * Stacking (Random Forest + XGBoost)
* Optimization:

  * Bayesian Optimization
* Evaluation Metrics:

  * Mean Squared Error (MSE)
  * R² Score

## Results

| Model                        | MSE    | R² Score |
| ---------------------------- | ------ | -------- |
| Random Forest                | 135.14 | 0.9098   |
| XGBoost                      | 4.04   | 0.9973   |
| Stacking + Linear Regression | 3.77   | 0.9975   |
| Stacking + Lasso Regression  | 3.76   | 0.9975   |

The Stacking model with Lasso Regression achieved the best predictive performance.

## Authors

* Evan Santosa
* Elena Nathanielle Angkawi

Universitas Bina Nusantara, Jakarta, Indonesia.
