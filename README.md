# 💳 Credit Card Fraud Detection

## 📌 Overview  
An end-to-end machine learning project for detecting fraudulent credit card transactions using multiple classification algorithms. This interactive Jupyter notebook demonstrates the entire workflow from exploratory data analysis to model evaluation and business impact assessment.

## 📂 Project Description  
This project analyses the [Credit Card Fraud Detection dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) from Kaggle, which contains transactions made by European cardholders. The dataset presents a real-world challenge: it's highly imbalanced with fraudulent transactions accounting for only **0.172%** of all observations.

## 🚀 Project Features  
- **Comprehensive EDA** with visualisations of transaction patterns  
- **Data preprocessing** including feature scaling and preparation  
- **Class imbalance handling** using SMOTE (Synthetic Minority Over-sampling Technique)  
- **Multiple ML models** comparison:  
  - Logistic Regression with class weights  
  - Random Forest Classifier  
  - Gradient Boosting  
  - XGBoost  
- **Detailed model evaluation** using metrics appropriate for imbalanced classification:  
  - Precision, Recall, F1 Score  
  - ROC Curves and AUC  
  - Confusion Matrices  
- **Classification threshold optimisation** to balance precision and recall  
- **Feature importance analysis** to identify key fraud indicators  
- **Business impact assessment** including financial cost-benefit analysis  

## 🛠 Getting Started  

### ✅ Prerequisites  
- Python 3.8+  
- Jupyter Notebook  
- Required libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `imbalanced-learn`, `xgboost`

## 🔍 Key Insights  

### 📊 Exploratory Data Analysis  
- Analysis of transaction amounts and their relationship with fraudulent activities  
- Visualisation of class imbalance and its implications for modelling
![class-imbalance](https://github.com/user-attachments/assets/9dcdbdcf-20ae-414e-9e36-9635bf1fdad5)
  
### 🧪 Model Performance  
- Comparison of different algorithms using metrics suitable for fraud detection  
- ROC and Precision-Recall curves to evaluate model discrimination capabilities  

### ⚙️ Threshold Optimisation  
- Finding the optimal classification threshold that balances fraud detection rate with false alarms  
- Visualisation of how different thresholds affect precision, recall, and F1 score  
![confusion-matrix](https://github.com/user-attachments/assets/fff72f2d-bb7c-40ff-bee3-67001704defd)

### 💼 Business Value  
- Quantification of potential savings from implementing the fraud detection system (based on hypothetical values used for illustration)
- Analysis of costs associated with false positives and false negatives
![financial-impact](https://github.com/user-attachments/assets/46ef5c02-d954-4abe-ac93-25a0b0c61058)


## ✅ Conclusion and Key Takeaways  
This project demonstrates how machine learning can be effectively applied to detect fraudulent credit card transactions, even with highly imbalanced data. The key findings include:

1.  **Model Selection Matters**: Tree-based models like XGBoost and Random Forest tend to perform well due to their ability to capture complex patterns.  
2.  **Beyond Default Thresholds**: Business-aware threshold tuning can significantly improve model utility.  
3.  **Cost-Sensitive Evaluation**: False negatives are typically more costly than false positives.  
4.  **Operational Considerations**: Speed matters—fraud detection must work in real time.  
5.  **Continuous Improvement**: Fraud patterns change—models need constant updates.  

The techniques demonstrated are directly applicable to real-world fraud detection in banking environments.

## 🔮 Future Work  
-  Develop an API for real-time fraud detection  
- 🛠 Implement more advanced feature engineering techniques  
-  Explore deep learning approaches for fraud detection  
-  Create a monitoring system for model performance over time  

---

*📚 This project was created as a demonstration of fraud analytics capabilities for financial institutions.*
# credit-card-fraud-detection
ML-based credit card fraud detection with SMOTE, threshold tuning, and cost-benefit analysis.
