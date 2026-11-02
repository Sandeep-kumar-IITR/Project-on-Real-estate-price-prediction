# Bengaluru House Price Prediction

A supervised machine-learning project exploring residential property-price estimation using features such as location, area, size and room count.

## Problem

Estimate a property's price from selected listing attributes. The original notebook explores data preparation, exploratory analysis and several regression models.

## Workflow

1. Load and inspect the Bengaluru housing dataset.
2. Handle missing and inconsistent values.
3. Convert categorical features into model-ready representations.
4. Explore distributions and relationships through visualization.
5. Investigate outliers and feature quality.
6. Train and compare regression models.

## Models explored

- Linear Regression
- Lasso Regression
- Decision Tree Regression

## Repository contents

| File | Description |
|---|---|
| `Bengaluru_House_Data.csv` | Housing dataset |
| `banglore_home_prices_model.ipynb` | Data preparation, analysis and model experiments |

## Technology

Python · Pandas · NumPy · Matplotlib · scikit-learn · Jupyter Notebook

## Run locally

```bash
git clone https://github.com/Sandeep-kumar-IITR/Project-on-Real-estate-price-prediction.git
cd Project-on-Real-estate-price-prediction
python -m venv .venv
# Windows: .venv\\Scripts\\activate
# macOS/Linux: source .venv/bin/activate
pip install pandas numpy matplotlib scikit-learn jupyter
jupyter notebook
```

Open `banglore_home_prices_model.ipynb` and run the cells in sequence.

## Evaluation notes

The repository should document the final feature set, target units, train/test split, model hyperparameters and evaluation metrics (for example MAE, RMSE and R²). Use a split strategy that reflects the intended prediction setting; avoid reporting training-set performance as generalization performance.

## Disclaimer

This is an educational machine-learning project. Predictions are estimates based on historical data and should not be used as property valuations without independent verification.

## Author

**Sandeep Kumar** · [GitHub](https://github.com/Sandeep-kumar-IITR)
