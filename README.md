🩺 Diabetes Prediction Model (Advanced ML Project)
📌 Project Overview

This project is a Machine Learning model that predicts whether a person is diabetic based on demographic, lifestyle, and medical features.

It is a binary classification problem:

0 → Non-Diabetic
1 → Diabetic
📊 Dataset Information
Total Records: 100,000
Features: 8
Target Variable: diabetes
🔢 Features Description
Feature	Description
gender	Male / Female
age	Age of person
hypertension	0 = No, 1 = Yes
heart_disease	0 = No, 1 = Yes
smoking_history	never, current, former, No Info
bmi	Body Mass Index
HbA1c_level	Average blood sugar level
blood_glucose_level	Current glucose level
diabetes	Target (0/1)
🚀 Key Features of Project
Large-scale dataset handling (100k rows)
Categorical feature encoding (gender, smoking_history)
Data preprocessing and cleaning
Feature scaling
Model training and evaluation
Binary classification
🛠️ Technologies Used
Python 🐍
Pandas
NumPy
Scikit-learn
Matplotlib / Seaborn
⚙️ Installation

Clone the repository:

git clone https://github.com/yogeshyadav-07/diabetes-prediction.git
cd diabetes-prediction

Install dependencies:

pip install -r requirements.txt
▶️ Usage

Run the model:

python model.py

or (Notebook):

jupyter notebook model.ipynb
🔄 Model Workflow
Load dataset
Handle missing values / "No Info"
Encode categorical features:
Gender → Label Encoding
Smoking History → One-Hot / Label Encoding
Feature selection
Apply scaling (StandardScaler)
Train-test split
Train model (Logistic Regression / Random Forest / etc.)
Evaluate performance
📈 Example Prediction
Input:
[Male, 45, 1, 0, current, 28.5, 6.2, 150]

Output:
1 → Diabetic
📊 Model Performance
Accuracy: ~85% – 95% (depending on model & tuning)
Dataset size helps improve generalization

💡 Future Improvements
Hyperparameter tuning (GridSearchCV)
Feature importance analysis
Model saving (Pickle / Joblib)
Add API (Flask / FastAPI)
Add Streamlit UI
Deployment (Hugging Face / Render)
👨‍💻 Author

Yogesh Yadav

📜 License

This project is open-source under the MIT License.
