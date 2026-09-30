# 📊 Human Fertility Rate Prediction

> Regression project predicting human fertility rates from demographic and health indicators.

## The Problem
Fertility rates vary widely across regions and are influenced by demographics, healthcare access and socioeconomic factors. This project models those relationships to predict fertility rates.

## The Data
Fertility dataset (see `fertility data/`) with demographic and health-indicator features and fertility rate as the target.

## Approach
1. **EDA** — fertility rate distributions, correlations with demographic/health features, missing-value analysis.
2. **Feature engineering** — imputation, scaling, encoding of categorical indicators.
3. **Modeling** — train/test split; Build regression model.


## Tech Stack
Python · Pandas · NumPy · Scikit-learn · Matplotlib · Seaborn · Jupyter

## Project Structure
```
├── Human-fertility-rate-prediction.ipynb   # Full workflow
└── fertility data/                          # Dataset
```

## How to Run
```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
jupyter notebook Human-fertility-rate-prediction.ipynb
```
