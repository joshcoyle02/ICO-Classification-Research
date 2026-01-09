# 🔐ICO Cyber Incident Oracle 🔐

# 🎯 Project Essence:
Unveil the digital shadows by predicting cyber incidents within the ICO (Information Commissioner's Office) breach landscape. Leveraging real-world data breach reports, this project orchestrates a symphony of machine learning algorithms to forecast whether an incident bears the fingerprints of a cyber attack.

# 🛠 Dependencies:
Arm your arsenal with:

- pandas
- numpy
- matplotlib
- scikit-learn
- xgboost
- shap

# 📊 Dataset Deep Dive:
Drawing from ICO breach reports, the dataset illuminates the digital threat landscape across various sectors and sub-sectors. Each incident is meticulously catalogued with organizational details, breach characteristics, and the critical question: Is it a cyber incident?
Features Explained:

Sector/SubSector: The organizational domain where the breach occurred
ISCyberIncident: The binary heartbeat of our prediction (Yes/No - our target)
Temporal markers: When incidents were received and completed
Sector_Weight & SubSector_Weight: Engineered features capturing sector-specific cyber risk profiles

# 🚀 Approach:

Data Fortification: Cleansed the dataset of temporal noise and missing values, focusing on the core breach characteristics.
Threat Intelligence Engineering: Calculated sector-specific cyber incident rates, transforming categorical sectors into weighted risk scores that capture the unique threat profile of each domain.
Feature Encryption: Applied one-hot encoding and standard scaling to prepare the data for algorithmic consumption.
Ensemble Deployment: Orchestrated a battle-tested ensemble including:

XGBoost (The Champion)
Logistic Regression
Random Forest
Multi-Layer Perceptron (MLP)

