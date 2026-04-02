# Customer-Transaction-Prediction
End-to-end machine learning project for predicting customer transactions with feature engineering and model evaluation.


#  Customer Transaction Prediction

##  Project Overview
This project aims to predict whether a customer will make a transaction or not using machine learning techniques.

The dataset contains a large number of anonymized features, and the goal is to classify customers into:
- **0 → No Transaction**
- **1 → Transaction**

---

##  Dataset Description
- Dataset contains **200 features**
- Includes:
  - `ID_code` → Unique identifier (removed during preprocessing)
  - `target` → Output variable (0 or 1)
- Highly **imbalanced dataset (approx 9:1 ratio)**

---

##  Data Preprocessing
- Removed unnecessary column: `ID_code`
- Checked for missing values (none found)
- Analyzed data types and distributions
- Handled class imbalance (important for modeling)

---

##  Feature Engineering
New features were created to improve model performance:

- Mean
- Standard Deviation
- Minimum & Maximum values
- Sum of features
- Positive & Negative value counts
- Range (max - min)

These features help capture hidden patterns in the data.

---

##  Model Building
- Split data into training and testing sets
- Applied machine learning classification techniques
- Evaluated model performance on test data

*(You can add model names like Logistic Regression, Random Forest, etc. if used)*

---

##  Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn

---

##  How to Run the Project

1. Clone the repository:
2. pip install -r requirements.txt
3. jupyter notebook

[git clone https://github.com/your-username/your-repo-name.git](https://github.com/praveentirkannavar/Customer-Transaction-Prediction)


## Accuracy score : 89% 
## ROC_AUC Score : 84%
