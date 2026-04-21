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

  ## Visualizations
  *Confusion Matrix: 
  <img width="1580" height="893" alt="Screenshot 2026-04-21 163507" src="https://github.com/user-attachments/assets/59c8c357-479a-4edf-9d7d-1ab1569d2ba4" />

*Feature Importance: 
<img width="1381" height="1102" alt="Screenshot 2026-04-21 164103" src="https://github.com/user-attachments/assets/5a36adb4-8f7a-4ce0-9ce8-40c16b0c134d" />


---

## Conclusion

This project demonstrates how machine learning can help organizations predict employee attrition and make data-driven decisions to improve retention strategies.
