# 🚢 Customer Survival Prediction System (Titanic Dataset)

## 📌 Project Overview

This project builds a Machine Learning classification model to predict whether a passenger survived the Titanic disaster.

Using historical passenger data, we apply data preprocessing, feature engineering, and classification algorithms to determine survival probability.

This project demonstrates the complete Machine Learning workflow:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Building
- Model Evaluation

---

## 🎯 Business Problem Statement

In real-world scenarios such as insurance, banking, and risk management, predicting customer survival or churn is critical.

This project attempts to answer:

1. What factors influenced passenger survival?
2. Can we predict survival using demographic and travel-related data?
3. Which features have the strongest impact on survival outcomes?

By identifying key survival patterns, organizations can better understand risk factors and decision-making dynamics.

---

## 📊 Dataset Description

The dataset contains passenger information such as:

- PassengerId
- Pclass (Ticket Class)
- Name
- Sex
- Age
- SibSp (Siblings/Spouses aboard)
- Parch (Parents/Children aboard)
- Ticket
- Fare
- Cabin
- Embarked
- Survived (Target Variable)

The target variable:
- **Survived**
  - 1 = Survived
  - 0 = Did Not Survive

---

## 🧹 Data Preprocessing

The following preprocessing steps were performed:

- Checked dataset shape and structure
- Handled missing values (Age, Cabin, Embarked)
- Dropped irrelevant columns (e.g., Name, Ticket, Cabin where necessary)
- Converted categorical variables into numerical format
- Feature scaling (if applied)
- Split dataset into training and testing sets

---

## 📊 Exploratory Data Analysis (EDA)

Key insights explored:

- Survival rate by gender
- Survival rate by passenger class
- Age distribution of survivors vs non-survivors
- Impact of fare price on survival
- Correlation between features

Major Observations:

- Females had significantly higher survival rates.
- First-class passengers had better survival probability.
- Younger passengers showed different survival trends.

---

## 🤖 Machine Learning Models Used

The project applies classification algorithms such as:

- Logistic Regression
- Decision Tree Classifier
- Random Forest (if implemented)

### Why Classification?

Because the target variable (Survived) is binary:
- 0 → Did not survive
- 1 → Survived

---

## ⚙️ Model Training & Evaluation

The dataset was split into:

- Training Set
- Testing Set

Evaluation metrics used:

- Accuracy Score
- Confusion Matrix
- Classification Report
  - Precision
  - Recall
  - F1-Score

Model performance was analyzed to determine prediction reliability.

---

## 📈 Key Insights

- Gender is one of the strongest predictors of survival.
- Passenger class significantly influenced survival probability.
- Higher fare passengers were more likely to survive.
- Proper feature engineering improves classification accuracy.

---

## 🛠️ Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🚀 Skills Demonstrated

- Data Cleaning
- Handling Missing Values
- Categorical Encoding
- Feature Selection
- Model Training
- Model Evaluation
- Binary Classification

---

## 📌 Conclusion

This project demonstrates how machine learning can be applied to solve real-world classification problems.

By analyzing passenger data, we identified key factors influencing survival and built predictive models to classify outcomes with strong accuracy.

The project highlights the importance of:

- Feature engineering
- Proper preprocessing
- Model evaluation techniques

It serves as a foundational classification project for further exploration into advanced ML techniques.

---

## 🔮 Future Improvements

- Hyperparameter tuning
- Cross-validation
- Feature importance visualization
- Try advanced models (XGBoost, Gradient Boosting)
- Deploy as a web app using Flask or Streamlit

---
