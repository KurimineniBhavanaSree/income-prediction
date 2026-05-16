💰 Income Prediction System using Machine Learning

An end-to-end Machine Learning project that predicts whether an individual's annual income exceeds $50K based on demographic and employment-related information. The project includes data preprocessing, feature engineering, model training, evaluation, and deployment using Streamlit.

📌 Project Overview

This project was developed to analyze census-based data and build a classification model capable of predicting income categories. Multiple Machine Learning algorithms were implemented and compared to identify the best-performing model.

The workflow covers:

Data Cleaning & Preprocessing
Exploratory Data Analysis (EDA)
Feature Engineering
Outlier Handling
Handling Imbalanced Data using SMOTE
Model Training & Evaluation
Streamlit Web Application Deployment
🚀 Features
Comprehensive Data Preprocessing
Missing Value Handling
Outlier Detection & Treatment
Feature Engineering
Feature Selection using SelectKBest
SMOTE for Class Imbalance
Multiple Machine Learning Model Comparison
Interactive Streamlit Frontend
Model Serialization using Joblib
🛠️ Technologies Used
Programming Language
Python
Libraries & Frameworks
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
Imbalanced-Learn (SMOTE)
Streamlit
Joblib
📂 Dataset Information

The dataset contains demographic and employment-related information collected from census records.

Dataset Statistics
Total Records: 48,842
Total Features: 15
Target Variable: Income
Target Classes
>50K
<=50K
📊 Workflow
1️⃣ Data Cleaning & Preprocessing
Replaced missing values
Handled categorical and numerical data
Applied scaling and encoding techniques
2️⃣ Feature Engineering

Created additional features such as:

capital-diff
work-hours
age-squared
age-group
high-capital
3️⃣ Exploratory Data Analysis

Performed visualization and analysis using:

Countplots
Boxplots
Correlation Heatmaps
4️⃣ Handling Imbalanced Data

Used SMOTE to balance the target classes and improve model performance.

5️⃣ Feature Selection

Applied SelectKBest to identify the most important features affecting predictions.

🤖 Models Implemented

The following Machine Learning models were trained and evaluated:

Model	Accuracy
K-Nearest Neighbors (KNN)	76.5%
Logistic Regression	79.4%
MLP Classifier	79.7%
Random Forest Classifier	82.7%
Gradient Boosting Classifier	81.3%
Support Vector Machine (SVM)	79.1%
🏆 Best Performing Model
Random Forest Classifier
Accuracy: 82.7%
Achieved the best performance among all implemented models.
💻 Streamlit Web Application

A user-friendly Streamlit application was developed to:

Input user demographic details
Predict income category
Display prediction confidence
Visualize important model insights
📁 Project Structure
Income-Prediction-System/
│
├── app.py
├── best_model.pkl
├── preprocessor.pkl
├── data.csv
├── requirements.txt
└── README.md
▶️ How to Run the Project
Clone the Repository
git clone https://github.com/your-username/Income-Prediction-System.git
Install Dependencies
pip install -r requirements.txt
Run the Streamlit Application
streamlit run app.py
