# Titanic_EDA
# Titanic Survival Prediction using Decision Tree

## Project Overview

This project analyzes the Titanic passenger dataset and builds a Decision Tree Classification model to predict passenger survival.

The project includes:

* Exploratory Data Analysis (EDA)
* Data Cleaning
* Missing Value Handling
* Feature Encoding
* Decision Tree Model Training
* Model Evaluation
* Feature Importance Analysis

---

## Dataset

Dataset: Titanic Survival Dataset

Target Variable:

* Survived

  * 0 = Did Not Survive
  * 1 = Survived

Features Used:

* Pclass
* Sex
* Age
* SibSp
* Parch
* Fare
* Embarked

Removed Features:

* PassengerId
* Name
* Ticket
* Cabin

---

## Exploratory Data Analysis (EDA)

The following analyses were performed:

* Dataset Overview
* Data Type Inspection
* Missing Value Analysis
* Summary Statistics
* Numerical Feature Analysis
* Categorical Feature Analysis
* Correlation Analysis

### Key Findings

* Survival was strongly influenced by passenger gender.
* Passenger class affected survival probability.
* Fare showed a significant relationship with survival.
* Age contributed to survival prediction.
* Some features contained missing values and were preprocessed before modeling.

---

## Machine Learning Model

Algorithm Used:

* Decision Tree Classifier

Workflow:

1. Load Dataset
2. Data Cleaning
3. Feature Encoding
4. Train-Test Split
5. Model Training
6. Prediction
7. Evaluation
8. Feature Importance Analysis

---

## Feature Importance

The most influential features identified by the model were:

1. Sex
2. Fare
3. Age
4. Pclass

These features contributed most to predicting passenger survival.

---

## Results

Model Accuracy:

(Add your accuracy score here)

Example:

Accuracy = 0.78

This indicates that the model correctly classified approximately 79% of passengers in the test dataset.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* Google Colab

---

## Future Improvements

* Random Forest Classifier
* Logistic Regression
* Hyperparameter Tuning
* Cross Validation
* Feature Engineering
* Model Comparison

---

## Learning Outcomes

Through this project I learned:

* Data preprocessing
* Exploratory Data Analysis
* Handling missing values
* Encoding categorical variables
* Building a classification model
* Evaluating model performance
* Interpreting feature importance

---
