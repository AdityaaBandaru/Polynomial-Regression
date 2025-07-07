# Polynomial-Regression
This project uses polynomial regression to predict an individual’s salary based on years of experience, past positions, companies worked at, and education level. After cleaning missing values, the model captures non-linear trends in salary growth to assist in HR and hiring decisions.

📂 Project Overview
Goal: Predict an individual's salary based on their experience, past roles, and education.
Technique: Polynomial Regression
Dataset: Custom dataset of 30 employees with Years_of_Experience, Previous_Companies, Last_Position, Education_Level, and Salary

🔧 Steps Performed
Data Cleaning

Handled missing values using SimpleImputer

Encoded categorical features numerically

Model Building

Trained a polynomial regression model using sklearn

Compared with a linear regression baseline

Visualization

Salary vs Experience curve

Polynomial regression fit

Residual analysis

📈 Results
The model captures the non-linear growth of salary with experience.
Polynomial regression showed better fit than linear, especially for higher experience levels.

📊 Model Visualization
Linear regression

![image](https://github.com/user-attachments/assets/d8d5738f-1035-4691-ad2b-51749f1674d5)

Polynomial Regression

![image](https://github.com/user-attachments/assets/9d21f1fe-a1cc-43d4-9411-6e5b351f1db2)


🛠️ Tech Stack
Python
Pandas, NumPy
Matplotlib
Scikit-learn


