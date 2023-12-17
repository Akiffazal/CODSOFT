# CODSOFT
# Titanic Survival Prediction Project

## Overview
This project aims to predict the survival of passengers on the Titanic using machine learning techniques. The dataset used for this analysis is the famous Titanic dataset, which includes information about passengers such as age, gender, class, and more.

## Project Structure
- **Data Exploration and Preprocessing:** The initial steps involve loading the dataset, exploring basic statistics, handling missing values, and creating new features based on existing ones.
- **Data Visualization:** Various plots and visualizations are created using Plotly and Matplotlib to gain insights into the distribution of survival, passenger classes, gender, age, fare, embarked locations, and more.
- **Multivariate Analysis:** A detailed multivariate analysis is conducted to explore the relationship between age, gender, fare, and survival, considering different facets.
- **Data Encoding and Balancing:** Label encoding is applied to categorical variables, and class imbalance is addressed using the Synthetic Minority Over-sampling Technique (SMOTE).
- **Model Building:** Logistic Regression, Random Forest, and Gradient Boosting classifiers are trained on the preprocessed data.
- **Model Evaluation:** The performance of each model is evaluated using classification reports and cross-validation scores.

## Instructions
1. **Dataset:** Make sure to provide the correct path to the Titanic dataset (`Titanic_Dataset.csv`) or update the file path accordingly.
2. **Dependencies:** Install the required libraries by running `pip install pandas numpy matplotlib plotly imbalanced-learn scikit-learn`.
3. **Run the Code:** Execute the code in a Python environment, and follow the step-by-step output to understand the data preprocessing, visualization, and model evaluation process.
4. **Explore Visualizations:** Review the generated visualizations to gain insights into the dataset and the factors influencing survival.
5. **Model Evaluation:** Examine the classification reports and cross-validation scores to understand the performance of each machine learning model.

