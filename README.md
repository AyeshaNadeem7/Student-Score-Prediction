📊 Project Objective:
Predict a student’s final exam score based on their academic and personal study habits using machine learning.

📦 Dataset:
Publicly available dataset from Kaggle with ~1000 entries, including the following features:

📚 Hours Studied

🧠 Previous Scores

💤 Sleep Hours

📄 Sample Question Papers Practiced

🏃‍♂️ Extracurricular Activities

🎯 Final Exam Score (Target)

🛠 Process:

Cleaned and preprocessed raw data using Pandas

Encoded categorical features (e.g., Yes/No → 1/0)

Visualized feature relationships using Seaborn heatmaps and pairplots

Built and evaluated models using:

📈 Linear Regression (R² ≈ 0.99 — excellent fit!)

🌀 Polynomial Regression (tested degrees 2 & 3 — did not outperform linear due to data's linear nature)

Validated with train/test split and calculated MSE, R² Score

📌 Key Insights Uncovered:

Strong positive correlation between Hours Studied and Final Score

Previous scores also significantly impacted prediction accuracy

Polynomial regression did not improve performance — the data had a mostly linear pattern

Linear regression gave the best results with excellent predictive accuracy

🧠 Technologies Used:

Python

Pandas

NumPy

Scikit-learn

Matplotlib / Seaborn
