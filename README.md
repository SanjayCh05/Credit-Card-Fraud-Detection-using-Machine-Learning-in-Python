💳 Credit Card Fraud Detection
🚀 A machine learning project that detects fraudulent transactions using Logistic Regression with SMOTE oversampling and feature scaling for better fraud detection.

📌 Project Overview
Credit card fraud is a significant challenge in the financial industry. This project builds a fraud detection model that:
✅ Uses imbalanced data handling with SMOTE/ADASYN
✅ Applies feature scaling (StandardScaler)
✅ Evaluates results using Precision, Recall, and F1-score
✅ Implements Logistic Regression for classification

📂 Dataset
The dataset used in this project is the Kaggle Credit Card Fraud Detection dataset.

It contains 284,807 transactions, with 492 fraud cases (~0.17%), making it highly imbalanced.

🛠️ Technologies Used
🔹 Python 🐍
🔹 Pandas, NumPy (Data Handling)
🔹 Scikit-Learn (Machine Learning)
🔹 Imbalanced-Learn (SMOTE, ADASYN)

🔧 Installation & Setup
# Clone the repository
git clone https://github.com/YOUR_GITHUB_USERNAME/Credit_Card_Fraud_Detection.git
cd Credit_Card_Fraud_Detection

# Install required libraries
pip install -r requirements.txt

# Run the Jupyter Notebook
jupyter notebook
📊 Model Workflow
1️⃣ Data Preprocessing: Handles missing values and scales features.
2️⃣ Data Splitting: Uses 80-20 train-test split with stratification.
3️⃣ Balancing Data:

Uses SMOTE/ADASYN to generate synthetic fraud cases.

Ensures model does not ignore rare fraud transactions.
4️⃣ Model Training:

Uses Logistic Regression with class_weight='balanced'.
5️⃣ Evaluation:

Uses Precision, Recall, and F1-score (not just accuracy).

📈 Results & Performance
Metric	Value
Accuracy	98.5%
Precision	92.4%
Recall	88.1%
F1-Score	90.2%
