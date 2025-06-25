# Feature-Engineering-Handling-Missing-Data
Feature engineering on the Titanic dataset using Python. Demonstrates handling missing values by imputing age (mean/median) and embarked (mode), and creates new features to improve data quality for machine learning. Includes code and examples for data preprocessing.

---

## Table of Contents

- Overview
- Dataset
- Feature Engineering Steps
- Getting Started
- Requirements
- Usage
- Results
- Contributing
- License
- Acknowledgments

---

## Overview

This notebook focuses on feature engineering for the Titanic dataset, a classic benchmark in data science and machine learning. The notebook guides users through loading the data, exploring missing values, and creating new features such as mean, median, and mode imputations for missing values. These steps are foundational for preparing data for machine learning models and ensuring data integrity[1].

---

## Dataset

- **Source:** The [Titanic dataset](https://www.openml.org/d/40945) is loaded directly via Seaborn's built-in datasets.
- **Features:** Includes passenger details such as survival status, class, sex, age, number of siblings/spouses aboard, fare, port of embarkation, and more.
- **Target Variable:** `survived` (binary: 0 = No, 1 = Yes)

---

## Feature Engineering Steps

The notebook covers the following key steps:

- **Loading Data:** Uses Seaborn to load the Titanic dataset.
- **Exploratory Data Analysis:** Inspects missing values and data types.
- **Handling Missing Values:**
  - Imputes missing `age` values using both mean and median strategies.
  - Imputes missing `embarked` values using the mode.
- **Feature Creation:** Adds new columns to the dataset (`age_mean`, `age_median`, `embarked_mode`) reflecting these imputations.
- **Data Visualization:** (Optional) Uses libraries like `missingno` and `seaborn` for visualizing missing data patterns.

---

## Getting Started

To run this notebook on your local machine:

1. **Clone the repository:**
   ```bash
   git clone 
   cd 
   ```

2. **Install required packages:**
   ```bash
   pip install pandas numpy seaborn missingno
   ```

3. **Open the notebook:**
   ```bash
   jupyter notebook Feature_Engineering_1.ipynb
   ```

---

## Requirements

- Python 3.x
- pandas
- numpy
- seaborn
- missingno

Install all dependencies with:
```bash
pip install -r requirements.txt
```

---

## Usage

- Run each cell in the notebook sequentially.
- The notebook demonstrates how to:
  - Inspect the dataset for missing values.
  - Impute missing values with statistical methods.
  - Add new engineered features to the dataset.
  - Optionally visualize missing data.

---

## Results

After running the notebook, you will have:

- A Titanic dataset with new features (`age_mean`, `age_median`, `embarked_mode`) that address missing values.
- An understanding of basic feature engineering techniques for tabular data.

---

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your improvements or suggestions.

---

## License

This project is licensed under the MIT License.

---

## Acknowledgments

- [Seaborn](https://seaborn.pydata.org/) for providing the Titanic dataset.
- [Pandas](https://pandas.pydata.org/) and [NumPy](https://numpy.org/) for data manipulation.
- [Missingno](https://github.com/ResidentMario/missingno) for visualizing missing data.

---
