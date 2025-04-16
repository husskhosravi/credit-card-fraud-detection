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

## ✅ Prerequisites  
- Python 3.8+  
- Jupyter Notebook  
- Required libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `imbalanced-learn`, `xgboost`

## 📊 Exploratory Data Analysis  
- Analysis of transaction amounts and their relationship with fraudulent activities  
- Visualisation of class imbalance and its implications for modelling
  
![class-imbalance](https://github.com/user-attachments/assets/752ce7d4-489b-46a9-83dc-20a955c83433)
  
## 🧪 Model Performance  
- Comparison of different algorithms using metrics suitable for fraud detection  
- ROC and Precision-Recall curves to evaluate model discrimination capabilities  

![class-imbalance](https://github.com/user-attachments/assets/c2d7f037-b865-4b90-96b4-78cde94fc56f)

## ⚙️ Threshold Optimisation  
- Finding the optimal classification threshold that balances fraud detection rate with false alarms  
- Visualisation of how different thresholds affect precision, recall, and F1 score  

![confusion-matrix](https://github.com/user-attachments/assets/9e58713b-5eea-4785-b60b-8a59d97620c1)

## 💼 Business Value  
- Quantification of potential savings from implementing the fraud detection system (based on hypothetical values used for illustration)
- Analysis of costs associated with false positives and false negatives

![confusion-matrix](https://github.com/user-attachments/assets/37a6c0ad-ffc8-4cb4-a0cc-ae3ae463d420)

## 📊 Summary of Findings:

1. **Data Characteristics**:
   - The dataset contained **284,807 transactions** with **492 fraudulent cases (0.1727% fraud rate)**
   - Highly imbalanced dataset requiring special handling

2. **Best Model**:
   - **Random Forest** performed best with an **F1 Score of 0.8360**
   - Optimal threshold for classification: **0.75**

3. **Model Performance**:
   - **Precision**: **0.8681**
   - **Recall**: **0.8061**
   - **AUC**: **0.9695**

4. **Key Insights**:
   - Feature importance analysis revealed the most predictive transaction attributes
   - Adjusting the classification threshold significantly impacts the balance between catching fraud and false alarms
   - SMOTE resampling was effective in handling the class imbalance problem
   - **Model selection matters** — tree-based models like Random Forest and XGBoost excel due to their ability to capture nonlinear fraud patterns
   - **Default thresholds are suboptimal** — tuning improves business value
   - **Cost-sensitive evaluation is crucial** — false negatives carry significantly higher cost than false positives
   - **Operational readiness is key** — real-time systems need speed and accuracy
   - **Fraud trends evolve** — continuous learning and updating are essential

5. **Business Value**:
   - The model provides substantial potential savings by detecting fraudulent transactions
   - Further optimisation could focus on reducing false positives to minimise investigation costs

## 🔮 Next Steps:
1. Implement a real-time fraud detection system using the trained model  
2. Establish continuous monitoring and periodic retraining to maintain effectiveness  
3. Explore additional features that could further improve fraud detection accuracy  

---

*📚 This project was created as a demonstration of fraud analytics capabilities for financial institutions.*
