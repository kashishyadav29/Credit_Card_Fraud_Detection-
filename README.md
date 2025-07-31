## Credit_Card_Fraud_Detection
# This project focuses on building a machine learning model to detect fraudulent credit card transactions using a real-world, anonymized dataset.

## 📌 Objective
# To accurately identify fraudulent transactions from a highly imbalanced dataset using supervised learning techniques.

## 🔍 Dataset
# -> Features: Anonymized variables (V1 to V28), Time, and Amount
# -> Target: Class (0 = Non-Fraud, 1 = Fraud)

## 🔧 Workflow
# => Exploratory Data Analysis (EDA):
  # -> Visualized class distribution
  # -> Correlation heatmap of features
# => Data Preprocessing:
  # -> Feature scaling for Amount and Time using StandardScaler
  # -> Dropped original Amount and Time columns

## Modeling:
# -> Trained a Logistic Regression model using scikit-learn
# => Evaluation:
# -> Confusion Matrix
# -> Classification Report (Precision, Recall, F1-score, Accuracy)

## 🛠️ Tools & Libraries
# -> Python
# -> Pandas, NumPy
# -> Matplotlib, Seaborn
# -> Scikit-learn

# 📈 Results
# The logistic regression model was able to capture fraudulent patterns with decent precision and recall, offering a solid baseline for further improvements.
