<h1>🩺 Diabetes Prediction Using Machine Learning</h1>
<ul>
  <li>This project focuses on predicting whether an individual is diagnosed with diabetes using a large-scale health and lifestyle dataset. The dataset contains 700,000 records with demographic, behavioral, physiological, and medical history features.</li>
  <li>The goal is to analyze risk factors and build machine learning models that can accurately predict diabetes diagnosis.</li>
</ul>
<h2>📌 Project Overview </h2>
<p></p>Diabetes is a growing global health concern. Early identification of high-risk individuals can help in prevention and better disease management. In this project, supervised machine learning techniques are applied to predict diagnosed_diabetes based on lifestyle habits, biometric measurements, and medical history. </p>

## 📂 Project Structure

```text
├── Diabetes_Prediction.ipynb
├── data/
│   └── diabetes_dataset.csv
└── README.md
```

<h2>📊 Dataset Information</h2>
Total records: 700,000
Total features: 26
Memory usage: ~139 MB
No missing values

<h2>🔢 Numerical Features</h2>
<ul>
  <li>age</li>
  <li>alcohol_consumption_per_week</li>
  <li>physical_activity_minutes_per_week</li>
  <li>diet_score</li>
  <li>sleep_hours_per_day</li>
  <li>screen_time_hours_per_day</li>
  <li>bmi</li>
  <li>waist_to_hip_ratio</li>
  <li>systolic_bp</li>
  <li>diastolic_bp</li>
  <li>heart_rate</li>
  <li>cholesterol_total</li>
  <li>hdl_cholesterol</li>
  <li>ldl_cholesterol</li>
  <li>triglycerides</li>
  <li>family_history_diabetes</li>
  <li>hypertension_history</li>
  <li>cardiovascular_history</li>
</ul>

<h2>🧾 Categorical Features</h2>
<ul>
  <li>gender</li>
  <li>ethnicity</li>
  <li>education_level</li>
  <li>income_level</li>
  <li>smoking_status</li>
  <li>employment_status</li>
</ul>



##🎯 Target Variable
```text
"diagnosed_diabetes"
1 → Diagnosed with diabetes
0 → Not diagnosed
```
<h2>⚙️ Technologies Used</h2>
<ul>
  <li><strong>Python</strong></li>
  <li><strong>Pandas</strong> – Data manipulation</li>
  <li><strong>NumPy</strong> – Numerical operations</li>
  <li><strong>Matplotlib &amp; Seaborn</strong> – Visualization</li>
  <li><strong>Scikit-learn</strong> – Model training &amp; evaluation</li>
  <li><strong>Jupyter Notebook</strong></li>
</ul>

<h2>🔍 Project Workflow</h2>
<ul>
  <li><strong>Data Loading &amp; Inspection</strong>
    <ul>
      <li>Dataset shape</li>
      <li>Data types</li>
      <li>Memory usage</li>
    </ul>
  </li>

  <li><strong>Exploratory Data Analysis (EDA)</strong>
    <ul>
      <li>Distribution analysis</li>
      <li>Correlation heatmaps</li>
      <li>Risk factor insights</li>
    </ul>
  </li>

  <li><strong>Data Preprocessing</strong>
    <ul>
      <li>Encoding categorical variables</li>
      <li>Feature scaling</li>
      <li>Train-test split</li>
    </ul>
  </li>

  <li><strong>Model Training</strong>
    <ul>
      <li>Logistic Regression</li>
      <li>Decision Trees</li>
      <li>Random Forest (if applied)</li>
    </ul>
  </li>

  <li><strong>Model Evaluation</strong>
    <ul>
      <li>Accuracy</li>
      <li>Precision, Recall, F1-score</li>
      <li>Confusion Matrix</li>
    </ul>
  </li>

  <li><strong>Prediction &amp; Analysis</strong>
    <ul>
      <li>Identifying key diabetes predictors</li>
    </ul>
  </li>
</ul>

<h2>🚀 How to Run the Project</h2>
<ol>
  <li>Clone the repository or download the files</li>
  <li>Install dependencies:
    <pre><code>pip install pandas numpy matplotlib seaborn scikit-learn</code></pre>
  </li>
  <li>Open the notebook:
    <pre><code>jupyter notebook Diabetes_Prediction.ipynb</code></pre>
  </li>
  <li>Run all cells sequentially</li>
</ol>

<h2>📈 Key Insights</h2>
<ul>
  <li>Lifestyle factors such as <strong>BMI, physical activity, diet score, and sleep</strong> strongly influence diabetes risk</li>
  <li>Medical history (hypertension, cardiovascular conditions, family history) significantly improves prediction accuracy</li>
  <li>Large dataset size helps reduce overfitting and improves generalization</li>
</ul>

<h2>🔮 Future Improvements</h2>
<ul>
  <li>Hyperparameter tuning</li>
  <li>Feature importance analysis</li>
  <li>Class imbalance handling</li>
  <li>Advanced models (XGBoost, LightGBM)</li>
  <li>Model deployment using Flask or FastAPI</li>
  <li>Interactive dashboard for predictions</li>
</ul>

<h2>⚠️ Disclaimer</h2>
<p>
This project is intended for <strong>educational and research purposes only</strong> and should not be used as a medical diagnostic tool.
</p>
<p>
All data has been collected from <strong>Kaggle Competitions</strong> related to Diabetes Prediction.
</p>

<h2>✨ Author</h2>
<p>
<strong>Drishyan Dahal</strong><br>
📧 <a href="mailto:drishyandahal4@gmail.com">drishyandahal4@gmail.com</a>
</p>
