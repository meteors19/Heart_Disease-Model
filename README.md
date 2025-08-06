# Heart_Disease-Model
A Predictive classified Machine Model on Heart_Disease Dataset

📋 Overview
This project aims to predict the likelihood of heart disease in patients based on medical attributes such as age, cholesterol levels, chest pain type, and more. It uses machine learning models to analyze real-world data and build a predictive system that supports early diagnosis and decision-making.

📁 Dataset
Source: UCI Heart Disease Dataset

Total Samples: 303

Features Include:

Age
Sex
Chest Pain Type (cp)
Resting Blood Pressure (trestbps)
Serum Cholesterol (chol)
Fasting Blood Sugar (fbs)
Resting ECG (restecg)
Max Heart Rate (thalach)
Exercise-Induced Angina (exang)
ST Depression (oldpeak)
Slope of ST Segment (slope)
Number of Major Vessels (ca)
Thalassemia (thal)
Target: Presence of heart disease (0 = No, 1 = Yes)

🧠 Models Used
Logistic Regression
Random Forest Classifier
Support Vector Machine (SVM)
K-Nearest Neighbors (KNN)

All models are evaluated using metrics like accuracy, precision, recall, and ROC-AUC score.

📊 Exploratory Data Analysis (EDA)
Performed using:
Matplotlib, Seaborn for visualization
Pandas, NumPy for cleaning and manipulation
Key insights:

Cholesterol levels are not always correlated with heart disease.
Chest pain type and exercise-induced angina show strong correlation with the target.
Most patients with heart disease are in the 40–65 age range.

📈 Performance
Model	Accuracy	ROC-AUC
Logistic Regression	85%	0.88
Random Forest	90%	0.93
SVM	82%	0.86

Note: Actual performance may vary slightly depending on train-test split and parameter tuning.

🧪 Tools & Libraries
Python 3.x
Pandas, NumPy
Scikit-learn
Matplotlib, Seaborn
Jupyter Notebook
Tableau (for visualization dashboard)

📊 Tableau Dashboard
An interactive Tableau dashboard was created to visualize:
Age group distribution
Chest pain type by gender
Cholesterol levels
No of Patients having maximum high heart rate


🙌 Acknowledgments
UCI Machine Learning Repository

scikit-learn, matplotlib, and pandas communities

🧑‍💻 Author
Abhishek Kumar
Data Science & Analytics Enthusiast


