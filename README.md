# 💼 Salary Prediction using Machine Learning

This project demonstrates how to use **machine learning models** to predict employee salaries based on factors like **Years of Experience, Education Level, and Gender**.  
It compares multiple regression techniques and visualizes the results for better interpretation.

---

## 📂 Dataset
The dataset contains employee salary information with the following columns:

- **Age** – Age of the employee  
- **Gender** – Male/Female  
- **Education Level** – Bachelor's, Master's, or PhD  
- **Job Title** – Employee’s job designation  
- **Years of Experience** – Total years of professional experience  
- **Salary** – Target variable (employee salary in USD)  

---

## 🛠️ Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/harishh09/salary-prediction.git
cd salary-prediction
pip install -r requirements.txt
```

## requirements.txt
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## 🚀 Models Implemented

The following models were trained and compared:
- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor
- Support Vector Regressor (SVR)

## 📊 Results
Model	R-squared	Mean Absolute Error
Linear Regression	0.913	$10,362.67
Gradient Boosting	0.903	$10,101.66
Random Forest	0.895	$10,217.87
SVR	-0.021	$40,479.08

🏆 Best Model: Linear Regression (Highest R² = 0.913)
