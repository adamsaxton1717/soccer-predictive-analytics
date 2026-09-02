# Soccer Predictive Analytics

> R-based predictive modeling framework using Random Forest and Principal Component Analysis (PCA) to forecast soccer league standings.

## Project Overview
* **Title:** European Soccer Performance & League Standing Prediction Model
* **Objective:** Predict team league standings (Top-10 vs. Bottom-10 classification) using player-level aggregate metrics and team performance data.

## Key Insights
* **Sample Size Sensitivity:** Filtering players by appearance thresholds (e.g., $>10$ or $>20$ appearances) isolates signal from noise, significantly improving out-of-sample prediction accuracy.
* **Dimensionality Reduction:** Applying Principal Component Analysis (PCA) captured primary variance drivers across 15+ performance metrics while effectively mitigating multicollinearity in linear regression modeling.

## Tech Stack & Methodology
* **Language:** R
* **Machine Learning:** Random Forest, Decision Trees (`randomForest`, `rpart`)
* **Statistical Methods:** Linear Regression, Principal Component Analysis (PCA / PCR)
* **Validation:** 10-Fold Cross-Validation, Out-of-Bag (OOB) error estimation, ROC/AUC Curves (`pROC`, `caret`)
* **Visualization:** `ggplot2`, `factoextra`, `gridExtra`

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/soccer-predictive-analytics.git](https://github.com/YOUR_USERNAME/soccer-predictive-analytics.git)