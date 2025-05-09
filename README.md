# Insurance Cost Analysis 🩺📊

This project focuses on analyzing a dataset related to health insurance costs and identifying the factors that most influence insurance charges. Using Python and various data science libraries, we perform data cleaning, exploratory data analysis (EDA), and predictive modeling through regression techniques.

---

## 📁 Dataset Description

The dataset contains the following parameters:

| Parameter         | Description                              | Type      |
|------------------|------------------------------------------|-----------|
| `age`            | Age in years                             | Integer   |
| `gender`         | Male or Female (1 or 2)                  | Integer   |
| `bmi`            | Body Mass Index                          | Float     |
| `no_of_children` | Number of children                       | Integer   |
| `smoker`         | Whether smoker or not (0 = No, 1 = Yes)  | Integer   |
| `region`         | US Region (1 = NW, 2 = NE, 3 = SW, 4 = SE)| Integer   |
| `charges`        | Annual Insurance Charges in USD          | Float     |

---

## 🎯 Objectives

- Load the dataset into a `pandas` DataFrame
- Clean the dataset and handle missing values
- Perform Exploratory Data Analysis (EDA) to identify trends and key influencing factors
- Develop:
  - **Simple Linear Regression**
  - **Multiple Linear Regression**
  - **Ridge Regression** models to predict insurance charges
- Evaluate and refine model performance

---

## 🔧 Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib & Seaborn (for visualization)
- Scikit-learn (for model building)

---

## 📊 Key Insights

- Analysis reveals strong correlation between smoking habits and insurance costs
- Regression models help quantify the impact of BMI, age, and other parameters
- Ridge regression improves model performance by addressing multicollinearity

---

## 🚀 How to Run

1. Clone the repository:

