{Work in Progress - First commit as a project plan}

# Loan Default Prediction Model Exercise

This repository contains a series of notebooks developed for a Model Developer position at a bank, demonstrating foundational techniques in synthetic data generation, data preparation, modeling, and analysis for predicting loan defaults. All work is original, with significant use of Generative AI. 



## Project Overview

The goal of this exercise is to create a loan default prediction model using a synthetic dataset. The model aims to predict whether a loan applicant is likely to default based on various features such as income, loan amount, credit history, and employment status.



## Key Steps

### Data Preparation
- **Generate and Clean Data**: Synthetic dataset generation with relevant features including income, loan amount, and credit history.
- **Exploratory Data Analysis (EDA)**: Analysis to understand distributions, handle outliers, and impute missing values.
- **Feature Engineering**: Simple outlier modifications for demonstration purposes; further engineering omitted for this synthetic dataset

### Model Development and Evaluation
1. **Logistic Regression Model**
   - Model configuration with hyperparameter tuning using cross-validation.
   - Evaluation through accuracy, precision, and f1-score
   
2. **Random Forest Model**
   - Setup and tuning of the Random Forest classifier.
   - Analysis of feature importance to identify key predictors of default.
   - Evaluation through accuracy, precision, and f1-score
   - Model validation and performance comparison against Logistic Regression.



### Reflections and Future Directions
{Work in Progress}



## Repository Contents

- `loan_default_data_preparation.ipynb`: Notebook for data cleaning and feature engineering.
- `loan_default_logistic_regression.ipynb`: Notebook demonstrating the development and evaluation of the Logistic Regression model.
- `loan_default_random_forest.ipynb`: Notebook for Random Forest model setup, tuning, and evaluation.
- `README.md`: This file, describing the project structure and how to run the notebooks.



## How to Run the Code

1. Clone this repository: `git clone https://github.com/GriffonCode/Banking-May.git`
2. Install required libraries: `pip install -r requirements.txt`
3. Open and run the Jupyter Notebooks:
   - `jupyter notebook loan_default_data_preparation.ipynb`
   - `jupyter notebook loan_default_logistic_regression.ipynb`
   - `jupyter notebook loan_default_random_forest.ipynb`

## Disclaimer

This project is designed as a practical demonstration of foundational modeling and data analysis capabilities for credit model development. The synthetic dataset used may not fully represent real-world complexities of loan data.

## Contact

For any questions or feedback, feel free to contact me here or by email, shared separately.