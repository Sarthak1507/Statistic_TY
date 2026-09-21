# Statistics Analysis Project (StatsPro)

A comprehensive Python project for statistical analysis of stock market data.

## Project Structure

```
Statistics-TY/
├── README.md
├── data/
│   └── StatsPro.xlsx
├── scripts/
│   ├── 01_data_loading.py
│   ├── 02_descriptive_stats.py
│   ├── 03_data_visualization.py
│   ├── 04_trend_analysis.py
│   ├── 05_normality_tests.py
│   ├── 06_correlation_analysis.py
│   ├── 07_hypothesis_testing.py
│   └── 08_statistical_summary.py
├── outputs/
│   ├── statistics_report.csv
│   ├── plots/
│   └── analysis_results.txt
└── utils/
    ├── __init__.py
    └── helpers.py
```

## Features

- **Data Loading & Exploration**: Load and explore the dataset
- **Descriptive Statistics**: Calculate mean, median, std, etc.
- **Visualization**: Generate plots and charts
- **Trend Analysis**: Analyze price trends and moving averages
- **Normality Tests**: Shapiro-Wilk and Anderson-Darling tests
- **Correlation Analysis**: Find correlations between variables
- **Hypothesis Testing**: Perform t-tests and other statistical tests
- **Statistical Summary**: Generate comprehensive reports

## Installation

```bash
pip install -r requirements.txt
```

## Usage

Run scripts in order:
```bash
python scripts/01_data_loading.py
python scripts/02_descriptive_stats.py
python scripts/03_data_visualization.py
python scripts/04_trend_analysis.py
python scripts/05_normality_tests.py
python scripts/06_correlation_analysis.py
python scripts/07_hypothesis_testing.py
python scripts/08_statistical_summary.py
```

Or run individual analysis:
```bash
python scripts/03_data_visualization.py
```

## Requirements

- Python 3.7+
- pandas
- numpy
- scipy
- matplotlib
- seaborn
- openpyxl

## Output Files

All analysis results are saved in the `outputs/` directory:
- CSV files with statistical summaries
- PNG plots and visualizations
- Text reports with findings

## Author

Sarthak Karpe
