# Binary Classification Model on Credit Card Default Dataset

## Overview
This project aims to predict whether a customer will default on their credit card payment using machine learning techniques. The dataset used in this project contains various customer attributes, including demographic, financial, and behavioral factors.

## Files in the Repository

- **Credit_card_default_EDA.ipynb**: Jupyter Notebook containing exploratory data analysis and visualizations.
- **README.md**: This README file providing an overview of the project.
- **credit-card-default.csv**: Original dataset containing information on credit card holders and their payment behavior.
- **feature_selection.csv**: Processed dataset after feature selection.
- **picklel.pickle**: Serialized model file for making predictions.
- **predictions_analysisl.csv**: File containing predictions and analysis of model performance.

## Dataset Description
The dataset used in this project consists of credit card holder information, including:
- **Demographics**: Age, Gender, Marital Status, Education Level.
- **Financial Features**: Bill Statement History, Payment Status, Credit Limit, Previous Payments.
- **Behavioral Features**: Number of months due, Amount paid, History of default payments.
- **Target Variable**: Whether the customer defaulted on their credit card payment (1 = Default, 0 = No Default).

## Project Workflow
1. **Exploratory Data Analysis (EDA)**
   - Understanding feature distributions
   - Identify patterns and understand the factors contributing to credit card
defaults
   - Visualizing relationships between features
3. **Feature Selection**
   - Identifying important features for the model
   - Removing redundant or less impactful features
4. **Model Training & Prediction**
   - Training machine learning models on selected features
   - Evaluating model performance using various metrics such as Accuracy, Precision, Recall, F1-score, and ROC-AUC.
5. **Results Analysis**
   - Interpreting prediction outcomes
   - Comparing different models

## Requirements
To run the notebook and analysis, install the following dependencies:
```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn
```

## How to Run the Project
1. Clone the repository:
   ```sh
   git clone https://github.com/udaypachigolla999/Binary-Classification-Model-on-Credit-Card-Default-Dataset.git
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Credit_card_default_EDA.ipynb
   ```
3. Run the notebook cells to explore the data and visualize insights.
4. Use `picklel.pickle` to make predictions on new data.
