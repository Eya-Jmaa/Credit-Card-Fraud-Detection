📋 Project Overview
This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The dataset used is highly imbalanced, with fraudulent transactions making up only a small fraction of the total data. The goal is to build a model that can accurately identify these rare fraudulent cases.

📊 Dataset
Source: creditcard.csv

Size: 284,807 transactions, 31 features

Features:

Time: Seconds elapsed between each transaction and the first transaction

V1–V28: Principal components obtained via PCA (anonymized)

Amount: Transaction amount

Class: Target variable (1 = Fraud, 0 = Non-Fraud)

Class Distribution:
Non-Fraud: 284,315 (99.83%)

Fraud: 492 (0.17%)

⚠️ Note: The dataset is highly imbalanced, which poses a challenge for model training.

🛠️ Tools & Libraries
The following Python libraries are used in this project:

pandas

numpy

matplotlib

seaborn

scikit-learn

📈 Data Understanding & Exploration
Key steps performed:

Loaded and inspected the dataset

Checked for missing values (none found)

Analyzed class imbalance

Generated summary statistics and visualizations

🧠 Machine Learning Model
A Logistic Regression model is implemented to classify transactions as fraudulent or legitimate.

Steps:
Data preprocessing (scaling)

Train-test split

Model training

Evaluation using accuracy score

🚀 How to Run
Ensure the dataset creditcard.csv is in the working directory.

Run the Jupyter notebook credit-card-fraud-detection.ipynb step by step.

The notebook includes:

Data loading and exploration

Model training and evaluation

Visualization of results
