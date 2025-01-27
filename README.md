#  Diabetes Prediction in Pima Indians: Exploratory Data Analysis and Regression Modeling

## Project Overview
This project explores and predicts diabetes in the Pima Indian population using the Pima Diabetes Dataset from the National Institute of Diabetes and Digestive and Kidney Diseases. The focus is on conducting Exploratory Data Analysis (EDA), identifying key patterns, handling data quality issues, and applying machine learning models to predict the likelihood of diabetes.

## Dataset Information
- **Dataset Source**: National Institute of Diabetes and Digestive and Kidney Diseases
- **Observations**: 750
- **Variables**: 9
- **Target Variable**: Outcome (Diabetes present: 1, Diabetes absent: 0)

## Objectives
1. **Exploratory Data Analysis (EDA)**: 
   - Univariate, Bivariate, and Multivariate analysis to examine distributions, outliers, and correlations.
   - Visualizations including histograms, KDE plots, count plots, box plots, heatmaps, and pair plots.

2. **Data Preprocessing**:
   - Handling missing and invalid values in features such as glucose, blood pressure, and BMI.
   - Imputation of missing values using mean/median techniques.

3. **Feature Engineering**:
   - Creation of new features like `SevenOrMorePregnancies` to enhance model prediction capabilities.

4. **Regression Modeling**:
   - Random Forest model to predict diabetes, based on the number of pregnancies and other features.
   - Evaluation of model performance using accuracy, precision, and F1 score.

## Key Features
- **Data Cleaning**: Addressing issues such as missing data and imbalanced classes.
- **Model Evaluation**: Confusion matrix, accuracy, precision, recall, and F1 score.

## Results
- **Model Performance**:
   - Random Forest achieved a testing accuracy of 84.07%

## Installation & Usage
### Requirements:
- Python 3.9
- Jupyter Notebook
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

### Install Dependencies
```bash
pip install requirements.txt