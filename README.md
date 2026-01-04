Breast Cancer Classification using Machine Learning
📌 Overview
This project classifies breast cancer tumors as malignant or benign using Machine Learning techniques.
The Wisconsin Breast Cancer Dataset is used with Naive Bayes and Support Vector Machine (SVM) models to compare performance and analyze feature importance.

🧠 Problem Statement
Early detection of breast cancer improves treatment success.
This project uses supervised ML algorithms to predict tumor type based on diagnostic features.

📊 Dataset
Name: Wisconsin Breast Cancer Dataset
Source: sklearn.datasets.load_breast_cancer
Samples: 569
Features: 30 numerical features
Target:
0 → Malignant
1 → Benign

⚙️ Technologies Used
Python
NumPy, Pandas
Matplotlib, Seaborn
Scikit-learn

🔄 Workflow
Data loading and preprocessing
Feature scaling
Train-test split
Model training:
Gaussian Naive Bayes
Support Vector Machine (SVM)
Hyperparameter tuning
Model evaluation
Ablation study

🤖 Models
Naive Bayes: Probabilistic classifier using Gaussian distribution
SVM: Separates classes using an optimal hyperplane (C, kernel, gamma tuned)

📈 Evaluation Metrics
Accuracy
Classification Report
Confusion Matrix

🔬 Ablation Study
Features were removed selectively to observe performance changes and identify important features.

✅ Results
SVM outperformed Naive Bayes
Feature scaling improved SVM accuracy
Certain features strongly influenced predictions
