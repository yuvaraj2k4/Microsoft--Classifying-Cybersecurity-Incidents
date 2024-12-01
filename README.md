# Microsoft--Classifying-Cybersecurity-Incidents
This project focuses on leveraging machine learning to enhance the efficiency of Security Operation Centers (SOCs) by classifying cybersecurity incidents into triage grades

Key Features:
Data Preprocessing: Handling missing values, feature engineering, and scaling to prepare the dataset for analysis.
Machine Learning Models: Training, evaluating, and tuning classification models (e.g., Random Forest, Gradient Boosting) with a focus on handling imbalanced datasets.
Performance Metrics: Evaluating the model using Macro-F1 Score, Precision, and Recall to ensure balanced performance across all triage classes.
Feature Importance: Analyzing key features that influence the classification decisions to provide actionable insights for SOC analysts.
Error Analysis: Identifying misclassifications to refine the model and improve accuracy.
Scalable Dataset: Working with a hierarchical dataset (Evidence → Alerts → Incidents) containing 1M triage-annotated incidents.

Technologies Used:
Programming Language: Python
Machine Learning: Scikit-learn, XGBoost, LightGBM
Visualization: Matplotlib, Seaborn
Frameworks: MITRE ATT&CK Framework for cybersecurity concepts
Tools: Git for version control

Applications
SOC Automation: Automating the triage process for cybersecurity incidents, enabling SOC analysts to focus on critical threats.
Incident Response: Enhancing guided response systems to provide actionable recommendations based on triage grades.
Enterprise Security: Reducing false positives to improve organizational security posture and operational efficiency.
