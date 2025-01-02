# Health-Data-Hypothesis-Testing

This repository contains statistical hypothesis testing analyses conducted on health data, specifically focusing on **insulin** and **cholesterol** levels from the NHANES dataset.

## Overview

The goal of this project is to explore differences in health biomarkers (insulin and cholesterol levels) between demographic groups (e.g., males and females) using hypothesis testing techniques. The analyses include:

- One-sample t-tests
- Two-sample independent t-tests
- Confidence interval estimation

These methods provide insights into whether observed differences are statistically significant.

## Data Source

The data used in this analysis is sourced from the **National Health and Nutrition Examination Survey (NHANES) 2021-2023**. NHANES provides publicly available health-related datasets, including demographic information and biomarker measurements.

### Variables Used
- **Insulin levels**: Measured in fasting plasma.
- **Cholesterol levels**: Total cholesterol measurements.
- **Demographic information**:
  - Gender (coded as 1 for males, 2 for females).

## Hypothesis Tests

### 1. Insulin Levels
**Research Question**: Are the average insulin levels significantly different between males and females?

- **Null Hypothesis (H₀)**: The mean insulin level for males is equal to the mean insulin level for females.
- **Alternative Hypothesis (Hₐ)**: The mean insulin level for males is not equal to the mean insulin level for females.
- **Statistical Test**: Two-sample independent t-test.
- **Results**: Provided in the analysis script.

### 2. Cholesterol Levels
**Research Question**: Are the average cholesterol levels significantly different between males and females?

- **Null Hypothesis (H₀)**: The average cholesterol level in the sample is not significantly different from a known population mean 200 mg/dL.
- **Alternative Hypothesis (Hₐ)**: The average cholesterol level in the sample is significantly different from a known population mean 200 mg/dL.
- **Statistical Test**: Two-sample independent t-test.
- **Results**: Provided in the analysis script.

## Repository Contents

- `data/`: Placeholder for input datasets (not included due to size).
- `notebooks/`: Jupyter notebooks containing code for data processing and hypothesis testing.
- `scripts/`: Python scripts for performing hypothesis tests.
- `README.md`: Documentation for the repository.

## Dependencies

- Python 3.8+
- Required libraries:
  - `pandas`
  - `numpy`
  - `scipy`


## Usage

1. **Data Preparation**:
   - Ensure the NHANES data files are downloaded and placed in the `data/` directory.
   - Load and clean the data using the scripts in the `scripts/` directory.

2. **Run Hypothesis Tests**:
   - Execute the notebooks in the `notebooks/` folder to reproduce the analysis.

3. **Interpret Results**:
   - The results of the hypothesis tests and confidence intervals are included in the output cells of the notebooks.


## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments
Special thanks to the **NHANES program** for providing publicly available datasets for health research.
