<h1>🩺 Diabetes Prediction Using Machine Learning</h1>
<ul>
  <li>This project focuses on predicting whether an individual is diagnosed with diabetes using a large-scale health and lifestyle dataset. The dataset contains 700,000 records with demographic, behavioral, physiological, and medical history features.</li>
  <li>The goal is to analyze risk factors and build machine learning models that can accurately predict diabetes diagnosis.</li>
</ul>
<h2> 📌 Project Overview </h2>h2>
<p></p>Diabetes is a growing global health concern. Early identification of high-risk individuals can help in prevention and better disease management. In this project, supervised machine learning techniques are applied to predict diagnosed_diabetes based on lifestyle habits, biometric measurements, and medical history. </p>

<h2>📂 Project Structure</h2>
├── Diabetes_Prediction.ipynb
├── data/
│   └── diabetes_dataset.csv
└── README.md

📊 Dataset Information
Total records: 700,000
Total features: 26
Memory usage: ~139 MB
No missing values

🔢 Numerical Features
age
alcohol_consumption_per_week
physical_activity_minutes_per_week
diet_score
sleep_hours_per_day
screen_time_hours_per_day
bmi
waist_to_hip_ratio
systolic_bp
diastolic_bp
heart_rate
cholesterol_total
hdl_cholesterol
ldl_cholesterol
triglycerides
family_history_diabetes
hypertension_history
cardiovascular_history

🧾 Categorical Features
gender
ethnicity
education_level
income_level
smoking_status
employment_status

🎯 Target Variable
diagnosed_diabetes
1 → Diagnosed with diabetes
0 → Not diagnosed

⚙️ Technologies Used
Python
Pandas – Data manipulation
NumPy – Numerical operations
Matplotlib & Seaborn – Visualization
Scikit-learn – Model training & evaluation
Jupyter Notebook

🔍 Project Workflow
Data Loading & Inspection
Dataset shape, data types, memory usage
Exploratory Data Analysis (EDA)
Distribution analysis
Correlation heatmaps
Risk factor insights
Data Preprocessing
Encoding categorical variables
Feature scaling
Train-test split
Model Training
Logistic Regression
Decision Trees
Random Forest (if applied)
Model Evaluation
Accuracy
Precision, Recall, F1-score
Confusion Matrix
Prediction & Analysis
Identifying key diabetes predictors

🚀 How to Run the Project
Clone the repository or download the files
Install dependencies:
pip install pandas numpy matplotlib seaborn scikit-learn

Open the notebook:
jupyter notebook Diabetes_Prediction.ipynb
Run all cells sequentially

📈 Key Insights
Lifestyle factors such as BMI, physical activity, diet score, and sleep strongly influence diabetes risk
Medical history (hypertension, cardiovascular conditions, family history) significantly improves prediction accuracy
Large dataset size helps reduce overfitting and improves generalization

🔮 Future Improvements
Hyperparameter tuning
Feature importance analysis
Class imbalance handling
Advanced models (XGBoost, LightGBM)
Model deployment using Flask or FastAPI
Interactive dashboard for predictions

⚠️ Disclaimer
This project is intended for educational and research purposes only and should not be used as a medical diagnostic tool.
All data has been collected from Kaggle Competitions of Diabetes Prediction

✨ Author
Drishyan Dahal
drishyandahal4@gmail.com
