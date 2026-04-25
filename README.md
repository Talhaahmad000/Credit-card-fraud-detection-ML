Credit Card Fraud Detection using Machine Learning
 Project Overview

This project detects fraudulent credit card transactions using a Machine Learning model.
It uses a Logistic Regression classifier trained on a balanced dataset to improve prediction performance on imbalanced data.

📊 Problem Statement

Credit card fraud is rare compared to normal transactions, making the dataset highly imbalanced.
This project solves that issue by:

Balancing the dataset
Training a classification model
Predicting fraud vs legitimate transactions
⚙️ Technologies Used
Python 🐍
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
📂 Dataset

The dataset contains credit card transactions with features representing transaction details.
Target column:

Class = 0 → Legit transaction
Class = 1 → Fraud transaction
🔄 Workflow
1. Data Loading

Load dataset using Pandas.

2. Data Preprocessing
Separate legit and fraud transactions
Undersample legit transactions to balance dataset
3. Feature Selection
Split into input features (X) and target (Y)
4. Train-Test Split
80% training data
20% testing data
Stratified split to maintain balance
5. Feature Scaling
StandardScaler applied for normalization
6. Model Training
Logistic Regression model used
7. Evaluation
Accuracy Score
Confusion Matrix
Classification Report
📈 Model Performance

The model is evaluated using:

Accuracy Score
Precision & Recall
Confusion Matrix visualization
📊 Confusion Matrix Visualization

Seaborn heatmap is used to visualize correct vs incorrect predictions.

🚀 How to Run
# Clone repository
git clone https://github.com/Talhaahmad000/fraud-detection.git

# Install dependencies
pip install -r requirements.txt

# Run the project
python main.py
🎯 Results

The model effectively identifies fraudulent transactions after balancing the dataset, improving classification performance on minority class (fraud cases).

📌 Future Improvements
Try Random Forest or XGBoost models
Use SMOTE instead of undersampling
Deploy using Flask or Streamlit
Add real-time fraud detection system
👨‍💻 Author

Talha Ahmad
