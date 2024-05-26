# Loan Default Prediction Model Exercise

This repository contains a series of notebooks developed for a Model Developer position at a bank, demonstrating foundational techniques in synthetic data generation, data preparation, modeling, and analysis for predicting loan defaults. All work is original, with significant use of Generative AI. 



## Project Overview

The goal of this exercise is to create a loan default prediction model using a synthetic dataset. The model aims to predict whether a loan applicant is likely to default based on various features such as income, loan amount, credit history, and employment status. 

A more complete model would go beyond simple binary default prediction and incorporate weights based on loan amounts to reflect the financial impact of defaults and aims to predict default probabilities as a function of time. This approach can lead to proactive measures such as reducing loan amounts or extending repayment periods to minimize potential losses. We leave this as a further improvement, and add some remarks in its appropriate section in this readme.  

## Key Steps

### Data Preparation
- **Generate and Clean Data**: Synthetic dataset generation with relevant features including income, loan amount, and credit history.
- **Exploratory Data Analysis (EDA)**: Analysis to understand distributions, handle missing values and duplicates
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

### Strengths of Choosing Logistic Regression and Random Forest Models

**Random Forest:**
- **Imbalanced Data**: Performs well with imbalanced datasets through techniques like class weighting or sampling within its structure.
- **Handling Non-Linearity**: Excels at capturing complex, non-linear relationships in the data due to its ensemble nature.
- **Feature Importance**: Provides clear insights into feature importance, aiding in feature selection and understanding of the model.
- **Versatility**: Can handle both numerical and categorical data efficiently without extensive preprocessing.
- **Robustness to Overfitting**: The aggregation of multiple decision trees reduces the risk of overfitting, leading to more generalized performance on unseen data.


**Logistic Regression:**
- **Simplicity and Interpretability**: Offers a straightforward approach with coefficients that are easy to interpret, making it clear how each feature impacts the prediction.
- **Efficiency**: Computationally efficient and performs well with large datasets, making it suitable for real-time applications.
- **Probability Outputs**: Provides probabilities for class membership, which can be useful for risk assessment and decision-making processes.
- **Baseline Performance**: Serves as a strong baseline model that can be quickly implemented and benchmarked against more complex models.
- **Regularization**: Supports regularization techniques (L1, L2) that can prevent overfitting and manage multicollinearity among features.


### Reflections and Future Directions
- **Weights Based on Default Amounts**: Future models should incorporate weights based on the loan amount to account for the financial impact of defaults. This approach ensures that larger loans, which pose a higher risk, are given more significance during model training.
- **Minimizing Losses**: To minimize potential losses, actions such as reducing loan amounts or extending the loan period could be considered. This can help borrowers manage repayments better and reduce the probability of default.
- **Time-Based Default Probability**: Enhancing the model to predict default probability as a function of time would provide more granular insights into when a borrower is most likely to default. This temporal aspect could lead to proactive measures, such as adjusting repayment schedules based on the predicted risk periods.
- **Improvements in Model Performance**: Plans to further refine hyperparameters, enhance feature engineering, and handle class imbalance more effectively.
- **Additional Models**: Exploration of other models like Gradient Boosting Machines and Neural Networks to improve performance.
- **Cross-Validation**: Implement k-fold cross-validation to ensure robust model evaluation.





## Repository Contents

- `loan_default_data_preparation.ipynb`: Notebook for data cleaning and feature engineering.
- `loan_default_logistic_regression.ipynb`: Notebook demonstrating the development and evaluation of the Logistic Regression model.
- `loan_default_random_forest.ipynb`: Notebook for Random Forest model setup, tuning, and evaluation.
- `data/loan_data.pkl`: Data file containing processed and prepared data for modeling.
- `model/random_forest_model.pkl`: Saved Random Forest model after training and tuning.
- `data/grid_search_log.txt`: Log of the hyperparameter tuning process for the Random Forest model.
- `utils/Gather_requirements.ipynb`: Notebook for gathering and listing Python package requirements.
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