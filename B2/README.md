# B2 – Predicting Wine Critic Scores

## Project Overview
This project predicts wine critic scores using wine tasting descriptions and metadata from the Wine Enthusiast dataset.

## Dataset
- Source: Kaggle – Wine Reviews
- Target variable: `points`
- Task: Supervised Regression
- Features: Tasting descriptions, price, country, province, and wine variety.

## Models
- Baseline Regression
- Ridge Regression
- SGDRegressor
- Gradient Boosting (Metadata-only)

## Best Model: Combined Ridge Regression

| Metric | Test Result |
|---|---:|
| MAE | 1.2180 |
| RMSE | 1.5603 |
| R² Score | 0.7454 |

## Ablation Study
Text-only features performed better than metadata-only features. Combining text and metadata achieved the best performance.

## Project Files
- `B2_Wine_Reviews.ipynb` – Complete notebook
- PNG files – EDA graphs and residual plot

## Dataset Source
https://www.kaggle.com/datasets/zynicide/wine-reviews
