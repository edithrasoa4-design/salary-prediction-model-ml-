# 💼 Salary Prediction Using Machine Learning

## 📌 Project Overview

This project builds a Machine Learning model to help the HR department predict candidate salaries based on:

- Years of Experience  
- Written Test Score  
- Interview Score  

Using historical hiring data (`hiring.csv`), a regression model is trained to estimate salaries for future candidates.

---

## 🎯 Business Problem

The HR department wants a data-driven way to determine appropriate salaries for new candidates based on measurable performance factors.

Instead of manual estimation, this model provides an objective and consistent salary prediction system.

---

## 📊 Dataset Description

The dataset (`hiring.csv`) contains:

- Experience (in years)
- Test Score (out of 10)
- Interview Score (out of 10)
- Salary (target variable)

Each row represents a previously hired candidate.

---

## 🛠 Tools & Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Google Colab

---

## 🔎 Data Preparation

- Loaded dataset using Pandas
- Checked for missing values
- Cleaned and formatted data
- Separated features (X) and target variable (y)

---

## 🤖 Machine Learning Model

### Model Used:
**Linear Regression**

Since salary is a continuous numeric value, Linear Regression was chosen to model the relationship between:

Salary = f(Experience, Test Score, Interview Score)

The model learns the relationship between these variables and predicts salary accordingly.

---

## 📈 Model Training

- Features (X):
  - Experience
  - Test Score
  - Interview Score

- Target (y):
  - Salary

The model was trained using Scikit-learn's `LinearRegression()`.

---

## 🔮 Salary Predictions

The trained model was used to predict salaries for the following candidates:

1️⃣ Candidate A  
- 2 years experience  
- 9 test score  
- 6 interview score  

2️⃣ Candidate B  
- 12 years experience  
- 10 test score  
- 10 interview score  

The model generated salary predictions based on learned patterns from historical data.

(See notebook output for exact predicted values.)

---

## 📊 Key Insights

- Experience has a strong positive impact on salary.
- Higher test and interview scores also increase predicted salary.
- The model provides consistent and data-driven salary decisions.

---
## ▶️ How to Run This Project

1. Clone this repository:
git clone (https://github.com/edithrasoa4-design/salary-prediction-model-ml-)
2. Open the notebook in Google Colab or Jupyter Notebook
3. Run all cells to train the model and generate predictions

## 👩‍💻 Author

**Edith Rasoa**  
Aspiring Data Scientist | Tech4Dev  


