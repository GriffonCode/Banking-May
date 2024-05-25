<<<<<<< HEAD
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
   - Evaluation through metrics such as ROC-AUC, accuracy, and precision.
   
2. **Random Forest Model**
   - Setup and tuning of the Random Forest classifier.
   - Analysis of feature importance to identify key predictors of default.
   - Model validation and performance comparison against Logistic Regression.


## Version Overview
This project version addresses a synthetic dataset with a weak signal, which presents a significant challenge for the predictive models used. We applied both Logistic Regression and Random Forest models but found that neither could effectively predict outcomes given the dataset's limited features and signals. A concluding PCA analysis at the end of the random forest file `loan_default_random_forest.ipynb` visualzies

### Reflections and Future Directions
The results highlight the difficulty of working with low signal-to-noise data using traditional methods. Looking ahead, we plan to test more complex models, such as ensembles that combine several approaches to improve accuracy. We also intend to work with a synthetic dataset that has a stronger signal, which should better demonstrate the potential of these models.

Further developments will focus on refining our data processing and modeling techniques based on what we've learned from this version.



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
=======
# Banking-May
>>>>>>> 8ae1581426c84ebcb1e92e00fb10002ace64a75d
