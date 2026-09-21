# Statistic_TY 
Closing Share Price Prediction

## Project 

This statistics mini-project analyses 500 daily closing share prices from 21 September 2023 to 24 September 2025. It follows the same data-to-model workflow as the reference project, but uses time-series features that are appropriate for share prices.

## Objectives

- Clean and validate the closing-price data.
- Produce descriptive statistics and time-series visualisations.
- Create lag and moving-average predictors using only previous trading days.
- Fit a chronological linear-regression model.
- Evaluate predictions with MAE, RMSE and R².
- Explain the model's limitations.

## Dataset

`Data/StatsPro.xlsx` contains the supplied source workbook. The analysis reads the first 500 observations in `Sheet1`; the descriptive-statistics block below the data is deliberately excluded.

Fields used:

- `Date` — trading date
- `Close Price` — daily closing share price

Derived features:

- `Lag_1` — previous trading day's closing price
- `Lag_3` — closing price three trading days earlier
- `MA_3` — trailing three-day moving average, shifted one day
- `MA_5` — trailing five-day moving average, shifted one day

## Project workflow

Dataset → Cleaning → Exploratory analysis → Feature engineering → Chronological train/test split → Linear regression → Prediction → Evaluation → Interpretation

## Structure

```text
share-price-statistics-project/
├── Data/
│   └── StatsPro.xlsx
├── Report/
│   └── Project_Report.md
├── notebooks/
│   ├── share_price_analysis.ipynb
│   └── share_price_analysis.py
├── requirements.txt
└── README.md
```

## Run the analysis

```powershell
cd share-price-statistics-project
python -m pip install -r requirements.txt
python notebooks/share_price_analysis.py
```

The script saves charts and predictions to `outputs/` inside this project.

## Important limitation

The supplied dataset contains only past closing prices. This is an educational baseline, not investment advice and not a reliable trading system. A negative test R² would mean the model does not improve on predicting the test-period average.
