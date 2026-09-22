# Statistical Analysis Project Report

## Statistical Analysis of Dataset Using Python

---

## 1. Project Information

| Detail | Information |
|---|---|
| **Project Title** | Statistical Analysis of Dataset Using Python |
| **Student Name** | Sarthak Karpe |
| **Course** | B.Sc. Information Technology |
| **College** | Nowrosjee Wadia College, Pune |
| **Academic Year** | 2026–2027 |
| **Programming Language** | Python |
| **Analysis Environment** | Jupyter Notebook / VS Code |
| **Dataset** | `Statics_data.xlsx` |

---

## 2. Introduction

Statistical analysis is an important process used to understand, summarize, visualize, and interpret data. It helps identify patterns, relationships, trends, and significant differences within a dataset.

This project performs statistical analysis using Python and Jupyter Notebook. The project uses an Excel dataset named `Statics_data.xlsx` and applies different statistical techniques to understand the characteristics of the data.

Python libraries such as Pandas, NumPy, SciPy, Matplotlib, Seaborn, and OpenPyXL are used throughout the project.

The analysis is divided into multiple notebooks, with each notebook focusing on a specific statistical technique.

---

## 3. Problem Statement

Large datasets can be difficult to understand by examining individual records manually. Statistical methods provide systematic techniques for organizing, summarizing, visualizing, and analyzing data.

The objective of this project is to develop a structured statistical analysis workflow that can process the given dataset and apply descriptive statistics, visualization, trend analysis, normality testing, correlation analysis, and hypothesis testing.

---

## 4. Objectives

The main objectives of this project are:

1. To load and understand the given dataset.
2. To inspect the structure and quality of the data.
3. To identify missing values and prepare the data for analysis.
4. To calculate descriptive statistical measures.
5. To visualize important characteristics of the dataset.
6. To analyze trends in the data.
7. To perform normality tests.
8. To identify relationships between numerical variables using correlation analysis.
9. To perform hypothesis testing using suitable statistical tests.
10. To summarize the major statistical findings.

---

## 5. Dataset Description

The project uses the following Excel file:

```text
data/Statics_data.xlsx
```

The dataset is loaded using the Pandas library.

The initial analysis includes:

- Number of rows
- Number of columns
- Column names
- Data types
- Missing values
- Duplicate records, where applicable
- Numerical and categorical variables

### Dataset Summary

| Property | Value |
|---|---|
| Dataset Name | `Statics_data.xlsx` |
| File Format | Excel |
| Number of Rows | `[Enter value]` |
| Number of Columns | `[Enter value]` |
| Numerical Variables | `[Enter variables]` |
| Categorical Variables | `[Enter variables]` |
| Date/Time Variable | `[Enter variable, if applicable]` |

> Replace the bracketed values with the actual information obtained from `01_data_loading.ipynb`.

---

## 6. Tools and Technologies

### Programming Language

**Python**

Python is used for data processing, statistical calculations, visualization, and analysis.

### Libraries Used

| Library | Purpose |
|---|---|
| Pandas | Data loading and manipulation |
| NumPy | Numerical calculations |
| SciPy | Statistical tests |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| OpenPyXL | Reading Excel files |
| Jupyter | Interactive notebook environment |

---

## 7. Project Structure

```text
Statistic_TY/
│
├── notebook/
│   ├── 01_data_loading.ipynb
│   ├── 02_descriptive_stats.ipynb
│   ├── 03_data_visualization.ipynb
│   ├── 04_trend_analysis.ipynb
│   ├── 05_normality_tests.ipynb
│   ├── 06_correlation_analysis.ipynb
│   ├── 07_hypothesis_testing.ipynb
│   └── 08_statistical_summary.ipynb
│
├── data/
│   └── Statics_data.xlsx
│
├── outputs/
│   └── plots/
│
├── Report/
│   └── Project_Report.md
│
├── README.md
├── QUICK_START.md
├── JUPYTER_SETUP.md
├── PROJECT_INDEX.md
├── FILE_SUMMARY.md
├── requirements.txt
└── .gitignore
```

---

# 8. Methodology

The project follows a step-by-step statistical analysis process.

```text
Dataset
   ↓
Data Loading
   ↓
Data Cleaning and Preparation
   ↓
Descriptive Statistics
   ↓
Data Visualization
   ↓
Trend Analysis
   ↓
Normality Testing
   ↓
Correlation Analysis
   ↓
Hypothesis Testing
   ↓
Statistical Summary
```

---

## 9. Data Loading and Preparation

### Notebook

```text
notebook/01_data_loading.ipynb
```

The first stage loads the Excel dataset using Pandas.

The analysis includes:

- Reading the Excel file
- Displaying the first few records
- Checking dataset dimensions
- Inspecting column names
- Checking data types
- Checking missing values
- Processing date information where applicable
- Sorting data where required
- Preparing cleaned data for further analysis

The processed dataset is then used by the subsequent notebooks.

---

## 10. Descriptive Statistical Analysis

### Notebook

```text
notebook/02_descriptive_stats.ipynb
```

Descriptive statistics are used to summarize the main characteristics of the dataset.

The following measures are considered:

### Mean

The mean represents the average value of a variable.

### Median

The median represents the middle value after arranging the observations in order.

### Standard Deviation

Standard deviation measures the amount of variation or dispersion in the data.

### Minimum and Maximum

These values represent the smallest and largest observations.

### Percentiles

Percentiles help understand the distribution of observations at different points.

### Results

The actual descriptive statistics generated by the notebook should be recorded here.

| Variable | Mean | Median | Standard Deviation | Minimum | Maximum |
|---|---:|---:|---:|---:|---:|
| `[Variable 1]` | `[Value]` | `[Value]` | `[Value]` | `[Value]` | `[Value]` |
| `[Variable 2]` | `[Value]` | `[Value]` | `[Value]` | `[Value]` | `[Value]` |
| `[Variable 3]` | `[Value]` | `[Value]` | `[Value]` | `[Value]` | `[Value]` |

---

# 11. Data Visualization

### Notebook

```text
notebook/03_data_visualization.ipynb
```

Data visualization is used to represent statistical information graphically.

The project may use:

- Line charts
- Histograms
- Box plots
- Distribution plots
- Scatter plots
- Correlation heatmaps

Visualization helps identify patterns, distributions, possible outliers, and relationships that may not be immediately visible from numerical statistics.

Generated plots are stored in:

```text
outputs/plots/
```

---

# 12. Trend Analysis

### Notebook

```text
notebook/04_trend_analysis.ipynb
```

Trend analysis examines how selected variables change over time or across observations.

The analysis may include:

- Time-based observations
- Percentage or return calculations where applicable
- Moving averages
- Trend lines
- Regression-based analysis

### Trend Results

The major trend identified from the actual analysis should be recorded here:

> `[Enter the actual trend observed from the notebook results.]`

The conclusion should be based on the generated data and visualizations rather than assumptions.

---

# 13. Normality Testing

### Notebook

```text
notebook/05_normality_tests.ipynb
```

Normality testing determines whether selected numerical data approximately follows a normal distribution.

The result is generally interpreted using a statistical test and its p-value.

### General Interpretation

For a chosen significance level, commonly:

```text
α = 0.05
```

The hypothesis can be interpreted as:

- **Null hypothesis (H₀):** The data follows the assumed normal distribution.
- **Alternative hypothesis (H₁):** The data does not follow the assumed normal distribution.

The actual test results should be recorded from the notebook.

| Variable | Test Statistic | P-value | Interpretation |
|---|---:|---:|---|
| `[Variable 1]` | `[Value]` | `[Value]` | `[Result]` |
| `[Variable 2]` | `[Value]` | `[Value]` | `[Result]` |

---

# 14. Correlation Analysis

### Notebook

```text
notebook/06_correlation_analysis.ipynb
```

Correlation analysis measures the relationship between numerical variables.

A correlation coefficient generally ranges from:

```text
-1 to +1
```

A value closer to:

- `+1` indicates a strong positive relationship.
- `0` indicates little or no linear relationship.
- `-1` indicates a strong negative relationship.

The project calculates correlations between selected numerical variables and presents them using appropriate visualizations.

### Correlation Results

| Variable 1 | Variable 2 | Correlation |
|---|---|---:|
| `[Variable 1]` | `[Variable 2]` | `[Value]` |
| `[Variable 1]` | `[Variable 3]` | `[Value]` |
| `[Variable 2]` | `[Variable 3]` | `[Value]` |

> Correlation indicates association and does not by itself establish causation.

---

# 15. Hypothesis Testing

### Notebook

```text
notebook/07_hypothesis_testing.ipynb
```

Hypothesis testing is used to determine whether there is sufficient statistical evidence for a particular claim about the data.

The project includes appropriate statistical tests such as:

- One-sample t-test
- Paired t-test
- Two-sample t-test
- Mann-Whitney U test
- Levene's test
- Effect-size analysis

The appropriate test depends on the characteristics of the data and the research question.

---

## 15.1 One-Sample t-Test

A one-sample t-test can be used to compare the sample mean with a specified value.

### Hypotheses

**H₀:** The population mean is equal to the specified value.

**H₁:** The population mean is different from the specified value.

### Result

```text
Test Statistic: [Enter value]
P-value: [Enter value]
```

### Interpretation

`[Enter interpretation based on the actual p-value and chosen significance level.]`

---

## 15.2 Paired t-Test

A paired t-test compares two related measurements.

### Hypotheses

**H₀:** There is no significant difference between the paired measurements.

**H₁:** There is a significant difference between the paired measurements.

### Result

```text
Test Statistic: [Enter value]
P-value: [Enter value]
```

### Interpretation

`[Enter interpretation based on the actual result.]`

---

## 15.3 Two-Sample t-Test

A two-sample t-test compares the means of two independent groups.

### Result

```text
Test Statistic: [Enter value]
P-value: [Enter value]
```

### Interpretation

`[Enter interpretation based on the actual result.]`

---

## 15.4 Mann-Whitney U Test

The Mann-Whitney U test is a non-parametric method used to compare two independent groups when the assumptions of a parametric test may not be appropriate.

### Result

```text
U Statistic: [Enter value]
P-value: [Enter value]
```

### Interpretation

`[Enter interpretation based on the actual result.]`

---

## 15.5 Levene's Test

Levene's test is used to examine whether groups have equal variances.

### Result

```text
Test Statistic: [Enter value]
P-value: [Enter value]
```

### Interpretation

`[Enter interpretation based on the actual result.]`

---

# 16. Statistical Summary

### Notebook

```text
notebook/08_statistical_summary.ipynb
```

The final notebook consolidates important findings from the previous analysis stages.

The summary includes:

- Descriptive statistics
- Trend information
- Normality test results
- Correlation results
- Hypothesis test results
- Generated output files

The final statistical summary is saved in the project output directory.

---

# 17. Results

The final results should be based entirely on the actual output generated by the notebooks.

### Major Findings

1. **Data Characteristics:**  
   `[Enter the major characteristics of the dataset.]`

2. **Descriptive Statistics:**  
   `[Enter important descriptive-statistics findings.]`

3. **Visualization:**  
   `[Enter important patterns observed in the graphs.]`

4. **Trend Analysis:**  
   `[Enter the actual trend identified.]`

5. **Normality Testing:**  
   `[Enter the normality-test conclusion.]`

6. **Correlation Analysis:**  
   `[Enter important correlation findings.]`

7. **Hypothesis Testing:**  
   `[Enter the major hypothesis-testing findings.]`

---

# 18. Limitations

The project has the following possible limitations:

- The analysis depends on the quality and completeness of the provided dataset.
- Statistical conclusions depend on the selected variables and tests.
- Some statistical tests have assumptions that must be considered before interpretation.
- Correlation does not necessarily imply causation.
- Results may change if the dataset is updated or expanded.

---

# 19. Conclusion

This project demonstrates the application of statistical techniques using Python and Jupyter Notebook.

The project follows a structured workflow beginning with data loading and preparation and continuing through descriptive statistics, visualization, trend analysis, normality testing, correlation analysis, and hypothesis testing.

The use of Python libraries such as Pandas, NumPy, SciPy, Matplotlib, and Seaborn provides an efficient way to perform statistical calculations and visualize the results.

The final conclusions should be based on the actual results generated from `Statics_data.xlsx` and documented in the project notebooks.

---

# 20. Future Scope

The project can be extended in the future by:

1. Adding additional datasets.
2. Including more advanced statistical tests.
3. Adding interactive dashboards.
4. Performing predictive analysis.
5. Automating the analysis workflow.
6. Adding additional visualization techniques.
7. Comparing results across multiple datasets.
8. Improving the final statistical report.

---

# 21. References

The following resources can be used for understanding the technologies and statistical methods used in the project:

- Python Documentation
- Pandas Documentation
- NumPy Documentation
- SciPy Documentation
- Matplotlib Documentation
- Seaborn Documentation
- Jupyter Documentation
- OpenPyXL Documentation