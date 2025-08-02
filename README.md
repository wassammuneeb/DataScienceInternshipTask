

# Data Science Internship Tasks – DevelopersHub Corporation

This repository contains my work for the four main tasks of my Data Science & Analytics Internship.

---

## **Task 1: Exploring and Visualizing a Simple Dataset (Iris Dataset)**

### Objective

To understand how to read, summarize, and visualize a dataset using the Iris dataset.

### Approach

* Loaded the Iris dataset using `pandas`.
* Displayed dataset structure using `.shape`, `.columns`, `.head()`.
* Created:

  * Scatter plot for relationships between variables.
  * Histogram for data distribution.
  * Box plot to detect outliers and spread of values.
* Used `matplotlib` and `seaborn` for visualization.

### Results & Insights

* Clear patterns were observed between petal length/width and species.
* Some features show strong separation between species, which can be useful for classification.
* Box plots revealed some outliers in petal measurements.

---

## **Task 2: Credit Risk Prediction (Loan Prediction Dataset)**

### Objective

To predict whether a loan applicant is likely to default using classification models.

### Approach

* Loaded dataset and checked for missing values.
* Encoded categorical features (`education`, `self_employed`, `loan_status`) using `LabelEncoder`.
* Visualized:

  * Loan amount distribution by loan status.
  * Education vs loan status counts.
  * Income distribution by loan status.
* Trained a **Decision Tree Classifier** for prediction.
* Evaluated model using accuracy score and confusion matrix.

### Results & Insights

* The model achieved good accuracy on the test set.
* Income and loan amount had visible patterns linked to loan status.
* Categorical factors like education also influenced the loan approval outcome.

---

## **Task 3: Customer Churn Prediction (Churn Modelling Dataset)**

### Objective

To identify customers likely to leave the bank (churn) using machine learning.

### Approach

* Removed irrelevant columns (`RowNumber`, `CustomerId`, `Surname`).
* Encoded `Geography` and `Gender` using `LabelEncoder`.
* Split the dataset into training (80%) and testing (20%) sets.
* Trained a **Random Forest Classifier** to predict churn.
* Evaluated model performance using accuracy and classification report.
* Analyzed feature importance using a bar plot.

### Results & Insights

* The model performed well with high accuracy.
* Key features influencing churn were `Age`, `Balance`, and `EstimatedSalary`.
* Insights from feature importance can help the bank focus retention efforts on customers with high churn risk.

---

## **Task 4: Medical Insurance Cost Prediction**

### Objective

To predict individual medical insurance charges using linear regression and visualize feature impact.

### Approach

* Loaded and explored the dataset.
* Converted categorical variables into dummy/indicator variables using one-hot encoding.
* Visualized how BMI, age, and smoking status affect insurance charges using scatter plots.
* Trained a **Linear Regression** model to predict insurance charges.
* Evaluated model using **Mean Absolute Error (MAE)** and **Root Mean Squared Error (RMSE)**.
* Analyzed model coefficients to identify impactful features.

### Results & Insights

* The model showed that **smoking status**, **BMI**, and **age** have the most significant impact on charges.
* Evaluation metrics:

  * **Mean Absolute Error (MAE):** 4181.19
  * **Root Mean Squared Error (RMSE):** 5796.28
* Model Coefficients:

  | Feature           | Coefficient |
  | ----------------- | ----------: |
  | smoker\_yes       |    23651.13 |
  | children          |      425.28 |
  | bmi               |      337.09 |
  | age               |      256.98 |
  | sex\_male         |      -18.59 |
  | region\_northwest |     -370.68 |
  | region\_southeast |     -657.86 |
  | region\_southwest |     -809.80 |

---

## **Technologies Used**

* **Python**
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* Google Colab

---

## **Author**

**Wassam Muneeb**
*Data Science & Analytics Intern*
DevelopersHub Corporation

---


