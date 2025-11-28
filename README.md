# Datasets

A repository strictly dedicated to the hosting of various datasets for use with data science and machine learning projects.

## Overview

This repository provides a curated collection of datasets in various formats (CSV, JSON, etc.) that can be used for:
- Machine Learning model training and evaluation
- Data Science exploration and analysis
- Educational purposes and tutorials
- Research and experimentation

## Repository Structure

```
Datasets/
├── classification/     # Datasets for classification tasks
├── regression/         # Datasets for regression tasks
├── nlp/               # Natural Language Processing datasets
├── time-series/       # Time series datasets
├── misc/              # Miscellaneous datasets
└── *.csv              # Root-level datasets (various categories)
```

## Available Datasets

### Categorized Datasets

| Dataset | Category | Format | Description |
|---------|----------|--------|-------------|
| [iris.csv](classification/iris.csv) | classification | CSV | Classic Iris flower dataset for classification |

### Root-Level Datasets

| Dataset | Format | Description |
|---------|--------|-------------|
| [home_prices.csv](home_prices.csv) | CSV | Historical median home sale prices in the US |
| [median_income.csv](median_income.csv) | CSV | US median household income over time |
| [mortgage30.csv](mortgage30.csv) | CSV | 30-year fixed mortgage rate historical data |
| [spi.csv](spi.csv) | CSV | Consumer Price Index (CPI) data |
| [student_loan_debt.csv](student_loan_debt.csv) | CSV | Student loan debt statistics |
| [tuition-dataset.csv](tuition-dataset.csv) | CSV | College tuition costs over time |
| [cleaned_tuition_dataset.csv](cleaned_tuition_dataset.csv) | CSV | Cleaned version of college tuition data |
| [cleaned_tuition_dataset.xlsx](cleaned_tuition_dataset.xlsx) | XLSX | Cleaned college tuition data (Excel format) |
| [RITIS-Oct-2025.csv](RITIS-Oct-2025.csv) | CSV | Traffic speed and travel time data from RITIS |

## Usage

### Direct Download

You can download individual datasets directly from this repository by navigating to the appropriate category folder.

### Using with Python

```python
import pandas as pd

# Example: Load a CSV dataset directly from GitHub
url = "https://raw.githubusercontent.com/mhen125/Datasets/main/classification/iris.csv"
df = pd.read_csv(url)
print(df.head())
```

### Using with R

```r
# Example: Load a CSV dataset directly from GitHub
url <- "https://raw.githubusercontent.com/mhen125/Datasets/main/classification/iris.csv"
df <- read.csv(url)
head(df)
```

## Contributing

We welcome contributions! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on how to add new datasets to this repository.

## License

This repository is provided for educational and research purposes. Individual datasets may have their own licensing terms - please check the README file in each dataset's directory for specific licensing information.
