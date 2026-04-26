🚀 Machine Learning Projects: Customer Segmentation & F1 Strategy Analysis

> A comparative study of classification and regression models on real-world tabular datasets, focusing on performance optimization, model evaluation, and practical insights.

---

📊 1. Customer Segmentation using ML

🧠 Problem Statement

Businesses often struggle to understand diverse customer behaviors. This project builds ML models to segment customers into meaningful groups, enabling targeted marketing and personalization.


---

🎯 Objectives

Classify customers based on behavioral & demographic data

Compare multiple ML algorithms

Improve model performance using preprocessing & tuning

Derive actionable business insights



---

📂 Dataset

Structured tabular dataset

Mix of categorical + numerical features

Cleaned and preprocessed for modeling



---

⚙️ Workflow

Data Cleaning → Encoding → Train/Test Split → Model Training → Evaluation → Comparison


---

🧹 Preprocessing

Label Encoding for categorical variables

Handling missing values

Feature scaling (for SVM)

Stratified splitting



---

🤖 Models Implemented

Logistic Regression (baseline)

Random Forest (ensemble)

XGBoost (boosting) ⭐

Support Vector Machine (SVM)



---

📊 Evaluation Metrics

Accuracy

F1 Score

Confusion Matrix



---

📈 Results Summary

Model	Accuracy	Remarks

XGBoost	⭐ ~97%	Best performance
Random Forest	~95–96%	Strong ensemble
SVM	~93–95%	Sensitive to scaling
Logistic Regression	~90–92%	Baseline



---

🔍 Key Insights

Boosting models outperform linear and distance-based models

Proper preprocessing significantly impacts performance

Ensemble methods capture complex customer behavior patterns



---

📌 Conclusion

Customer segmentation using ML provides scalable and data-driven marketing strategies, with XGBoost emerging as the most effective model.


---


---

🏎️ 2. Formula 1 Strategy & Performance Analysis

🧠 Problem Statement

Formula 1 strategy involves complex decisions like tire selection and pit stops. This project models these decisions using machine learning and analyzes lap performance.


---

🎯 Objectives

Predict race strategies (classification)

Analyze lap time performance (regression)

Compare ML models across tasks

Understand feature impact on race outcomes



---

📂 Dataset

F1 race telemetry & strategy dataset

Includes:

Lap data

Tire compounds

Degradation metrics

Race progress variables




---

⚙️ Workflow

Data Cleaning → Feature Engineering → Model Training → Evaluation → Comparison


---

🧹 Preprocessing

Removed minimal missing values (<0.01%)

Feature scaling (for SVM)



---

🤖 Models Implemented

🔹 Classification (Strategy Prediction)

Logistic Regression

Random Forest

XGBoost ⭐

Support Vector Machine


---

📊 Evaluation Metrics

Classification

Accuracy

F1 Score

Confusion Matrix


---

📈 Results Summary

Classification

Model	Performance

XGBoost	⭐ ~96–97%
Random Forest	Strong
SVM	Moderate
Logistic Regression	Baseline


---

🔍 Key Insights

Strategy prediction (classification) is more reliable than lap time prediction

Lap time is influenced by hidden variables → harder to model

Feature engineering plays a crucial role in performance improvement

Tree-based models excel in structured racing data



---

📌 Conclusion

Machine learning can effectively model race strategies and performance trends, with classification tasks offering more stable and interpretable results than regression.


---

🛠️ Tech Stack

Languages: Python

Libraries: Pandas, NumPy, Scikit-learn

Models: XGBoost, Random Forest, SVM, Logistic Regression

Visualization: Seaborn, Matplotlib



---

⭐ Highlights

End-to-end ML pipeline implementation

Model comparison across multiple algorithms

Real-world datasets (business + sports analytics)

Strong performance (up to ~97% accuracy)



---
