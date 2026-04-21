# Employee Attrition Prediction

## Problem Statement

Employee attrition is a major concern for organizations as it leads to increased costs and loss of talent. This project aims to predict whether an employee is likely to leave the company using machine learning techniques.

---

## Dataset

* IBM HR Analytics Employee Attrition Dataset
* Features include:

  * Age, Job Role, Salary, Work Experience
  * Job Satisfaction, Work-Life Balance
  * Overtime, Department, etc.

---

## Approach

1. Data Cleaning and Preprocessing
2. Label Encoding for categorical variables
3. Feature Engineering
4. Feature Scaling
5. Model Training using Random Forest
6. Model Evaluation

---

## Model Used

* Random Forest Classifier

  * Number of estimators: 200

---

## Results

* Accuracy: ~83%
* Evaluated using:

  * Confusion Matrix
  * Classification Report

---

## Key Insights

* Employees working overtime are more likely to leave
* Low job satisfaction strongly correlates with attrition
* Younger employees show higher attrition rates

---

## Future Improvements

* Hyperparameter tuning
* Use advanced models (XGBoost, LightGBM)
* Deploy as a web application

---

## Tools Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib / Seaborn

---

## Conclusion

This project demonstrates how machine learning can help organizations predict employee attrition and make data-driven decisions to improve retention strategies.
