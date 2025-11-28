# Contributing to Datasets

Thank you for your interest in contributing to this datasets repository! This document provides guidelines for adding new datasets.

## Guidelines for Adding Datasets

### 1. Choose the Right Category

Place your dataset in the appropriate category folder:
- `classification/` - For classification tasks
- `regression/` - For regression tasks
- `nlp/` - For natural language processing tasks
- `time-series/` - For time series data
- `misc/` - For datasets that don't fit other categories

### 2. File Format Requirements

- **Preferred formats:** CSV, JSON, or other common data formats
- **Encoding:** UTF-8
- **Headers:** Include descriptive column headers
- **File naming:** Use lowercase with hyphens (e.g., `customer-churn.csv`)

### 3. Documentation Requirements

Each dataset should include documentation in a README.md file in the same directory containing:

- **Description:** Brief overview of the dataset
- **Features:** List and description of all columns/features
- **Target variable:** (if applicable) The column to predict
- **Statistics:** Number of samples, features, classes, etc.
- **License:** The license under which the data is provided
- **Source:** Original source of the data

### 4. Licensing Considerations

- Only contribute datasets that you have the right to share
- Clearly specify the license for each dataset
- Preferred licenses: Public Domain, CC0, CC-BY, MIT, Apache 2.0
- Do not upload proprietary or confidential data

### 5. Data Quality

Before submitting, ensure:
- No personally identifiable information (PII)
- No missing values without documentation
- Consistent formatting throughout the file
- Reasonable file size (< 50MB recommended for individual files)

## How to Contribute

1. Fork this repository
2. Create a new branch for your dataset
3. Add your dataset file(s) to the appropriate category folder
4. Update the category README.md with your dataset information
5. Update the main README.md dataset table
6. Submit a pull request with a clear description

## Questions?

If you have questions about contributing, please open an issue in this repository.
