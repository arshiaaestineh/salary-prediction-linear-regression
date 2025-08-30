
# Simple Linear Regression: Salary Prediction

## 📌 Project Overview
This project implements a **Simple Linear Regression** model to predict **Salary** based on **Years of Experience**.  
It uses a dataset named `Salary_Data.csv`, which contains two columns:
- **YearsExperience**: Independent variable (X)
- **Salary**: Dependent variable (y)

The purpose is to understand the linear relationship between work experience and salary, and to use this relationship for predictions.

---

## 📂 Dataset
The dataset consists of:
- **Rows**: Each row represents an employee.
- **Columns**:
  - `YearsExperience`: Years of work experience.
  - `Salary`: Annual salary.

---

## 🛠️ Technologies Used
- **Python**
- **pandas** → Data loading and preprocessing
- **numpy** → Numerical operations
- **matplotlib** → Data visualization
- **scikit-learn** → Model building and evaluation

---

## 📊 Steps Performed
1. **Load the dataset** using `pandas`.
2. **Data inspection**: `.head()`, `.shape`, `.isnull().sum()`
3. **Define features (X) and target (y)**.
4. **Split data** into training and testing sets (`train_test_split`).
5. **Train the model** using `LinearRegression`.
6. **Make predictions** on the test set.
7. **Evaluate the model** using:
   - Mean Squared Error (MSE)
   - R² Score
8. **Visualize results**:
   - Scatter plot of actual data.
   - Regression line showing predictions.

---

## 📈 Model Performance
- **Mean Squared Error (MSE)**: ~49,830,096.86
- **R² Score**: ~0.9024

The R² score indicates that the model explains about **90%** of the variance in salaries based on years of experience, which is a strong result for a simple linear model.

---

## 📷 Visualizations
- **Training Set Plot**: Shows actual training data points and the regression line.
- **Test Set Plot**: Shows actual test data points with predicted regression line.

---

## 🚀 Future Work
- Add more features (e.g., education, location, industry).
- Use **Multiple Linear Regression**.
- Try **Polynomial Regression** if the relationship is non-linear.
- Apply cross-validation for better evaluation.
- Deploy the model as a web application.
.
---

## 👤 Author
**Arshia Estineh**  
- **GitHub**: [Arshiaaestinehh](https://github.com/Arshiaaestineh)  
- **Email**: [arshiaestineh2005@icloud.com](mailto:arshiaestineh2005@icloud.com)  

---

## 📄 License
This project is for educational purposes and can be freely used or modified..




