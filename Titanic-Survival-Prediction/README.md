# Titanic Survival Prediction using Machine Learning

## Project Overview

This project predicts whether a passenger survived the Titanic disaster using machine learning techniques.

The project demonstrates a complete end-to-end data science workflow, including data exploration, preprocessing, feature engineering, model development, evaluation, and model comparison.

---

## Objectives

- Explore the Titanic dataset
- Clean and preprocess the data
- Engineer new predictive features
- Train multiple machine learning models
- Compare model performance
- Select the best-performing model

---

## Dataset

Source:
Kaggle Titanic Dataset

Training records: 891 passengers

Target Variable:

- Survived
    - 0 = Did Not Survive
    - 1 = Survived

---

## Exploratory Data Analysis

Key findings:

- Female passengers had significantly higher survival rates.
- First-class passengers survived more often.
- Children had better survival rates than adults.
- Family size influenced survival.
- Passenger titles extracted from names improved feature representation.

---

## Data Cleaning

The following preprocessing steps were performed:

- Removed Cabin due to excessive missing values.
- Removed PassengerId because it is not predictive.
- Filled missing Age values using the median.
- Filled missing Embarked values using the mode.

---

## Feature Engineering

New features created:

- FamilySize
- IsAlone
- Title
- Age_Group

---

## Models Trained

- Logistic Regression
- Decision Tree
- Random Forest

---

## Model Performance

| Model | Accuracy |
|--------|----------|
| Logistic Regression | 81.01% |
| Decision Tree | 76.54% |
| Random Forest | **83.24%** |

Random Forest achieved the highest performance and was selected as the final model.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- Joblib

---

## Project Structure

```
Titanic-Survival-Prediction/

│

├── data/

├── notebooks/

├── models/

├── images/

├── README.md

├── requirements.txt

└── .gitignore
```

---

## Future Improvements

- Hyperparameter tuning
- Cross-validation
- Feature importance visualization
- Model deployment using Flask or Streamlit

---

## Author

**Mayowa Shobande**

GitHub:
https://github.com/mayowa215
