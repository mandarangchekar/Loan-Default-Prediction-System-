# Loan Default Prediction System

This repository hosts the Loan Default Prediction System, which utilizes machine learning techniques to predict loan defaults based on historical loan data. This project aims to help financial institutions reduce risk and improve decision-making processes regarding loan approvals.

## Project Overview

The primary goal of this project is to create a predictive model that can accurately identify potential loan defaults before they occur. This model leverages various data preprocessing, exploratory data analysis, and machine learning techniques to provide reliable predictions.

## Repository Structure

- **Data_cleaning.ipynb**: Notebook dedicated to cleaning and preparing the dataset for analysis.
- **Data_analysis.ipynb**: Notebook containing detailed EDA, feature engineering, and model training and evaluation.
- **requirements.txt**: Lists all the dependencies necessary to run the notebooks.

## Getting Started

### Prerequisites

- Python 3.6+
- pip

### Installation

Clone this repository and install the required Python packages.

```bash
git clone https://github.com/your-username/Loan-Default-Prediction-System.git
cd Loan-Default-Prediction-System
pip install -r requirements.txt
```
## Detailed Workflow

### Data Cleaning (`Data_cleaning.ipynb`)

This notebook addresses various data quality issues such as:

- **Duplicate Values**: Identification and removal of duplicate records.
- **Missing Data**: Techniques like mean imputation, median imputation, or predictive modeling to fill missing values.
- **Outliers**: Detection and treatment of outliers using IQR score or z-score methods.

### Data Analysis and Model Building (`Data_analysis.ipynb`)

#### Exploratory Data Analysis (EDA)

- **Descriptive Statistics**: Summary statistics for numerical and categorical variables to get a sense of the data's central tendencies and spread.
- **Visualization**: Use of histograms, box plots, and scatter plots to understand distributions and relationships.
- **Correlation Analysis**: Heatmaps and correlation matrices to identify potential predictors of loan default.

#### Feature Engineering

- **Feature Creation**: Derivation of new features like debt-to-income ratio and credit utilization to enhance model performance.
- **Feature Transformation**: Application of transformations such as logarithmic or polynomial transformations to normalize data distributions.

#### Model Development

- **Logistic Regression**: A baseline model for binary classification tasks.
- **Random Forest Classifier**: An ensemble model known for its high accuracy and robustness against overfitting.
- **Gradient Boosting Machines (GBM)**: Advanced ensemble techniques that sequentially correct the mistakes of prior models and improve prediction accuracy.

#### Model Evaluation

- **ROC-AUC**, **precision**, **recall**, and **F1-score** are used to assess model performance.

