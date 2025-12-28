# Titanic Survival Prediction

## About the Project
This project is part of my **Data Science Internship at CodSoft**.  
The goal of this project is to predict whether a passenger survived the Titanic disaster using basic machine learning techniques.

This project helped me understand the complete data science workflow, starting from data cleaning to model evaluation.

---

## Dataset
- Dataset: Titanic Dataset
- Total Rows: 891
- Target Column: `Survived`
  - 0 → Passenger did not survive
  - 1 → Passenger survived

The dataset contains passenger details such as age, gender, ticket class, fare, and embarkation port.

---

## Data Cleaning & Preparation
Before training the model, the dataset was cleaned properly:
- Missing values in **Age** were filled using the median.
- Missing values in **Embarked** were filled using the most frequent value (mode).
- Columns like `PassengerId`, `Name`, `Ticket`, and `Cabin` were removed as they are not useful for prediction.
- Categorical columns were converted into numerical form for model training.

After preprocessing, the dataset had no missing values.

---

## Exploratory Data Analysis (EDA)
Some visualizations were created to understand the data better:
- Survival count of passengers
- Survival comparison based on gender
- Survival comparison based on passenger class
- Age distribution of passengers

These plots helped identify important patterns in the dataset.

---

## Model Used
- **Algorithm:** Logistic Regression  
- **Reason:** Simple, easy to understand, and suitable for binary classification problems.

The dataset was split into:
- 80% training data
- 20% testing data

---

## Results
- **Accuracy achieved:** 80%

The model performed well after proper preprocessing and feature selection.

---

## Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Conclusion
This project gave me hands-on experience with data preprocessing, visualization, and machine learning model training.  
Logistic Regression provided good results for this problem and helped me understand how classification models work in practice.

---

## Author
**Aslam Ansari**  
Data Science Intern – CodSoft
