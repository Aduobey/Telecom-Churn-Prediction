# 📊 Telco Customer Churn Prediction

## 📝 Project Overview
This project analyzes customer churn in a telecom company and builds predictive models to classify whether a customer is likely to churn. The dataset used is publicly available and contains customer demographics, account details, and service usage.

## 🚀 Features
- Data Preprocessing (handling missing values, encoding categorical variables, scaling numeric features)
- Model Training & Evaluation (Logistic Regression, Random Forest, XGBoost)
- Performance Metrics (Accuracy, Precision, Recall, AUC-ROC)
- Visualizations (Churn Distribution, Confusion Matrix, ROC Curve)

## 📂 Dataset
**Source:** `WA_Fn-UseC_-Telco-Customer-Churn.csv`
- `Churn`: Target variable (Yes/No)
- `TotalCharges`: Converted to numeric (handling missing values)
- Categorical features: One-hot encoded

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- XGBoost

## 🏆 Model Performance
| Model                 | Accuracy | Precision | Recall | AUC-ROC |
|----------------------|----------|----------|--------|--------|
| Logistic Regression  | 85%      | 78%      | 72%    | 0.86   |
| Random Forest        | 83%      | 75%      | 68%    | 0.84   |
| XGBoost             | 86%      | 80%      | 74%    | 0.88   |

## 📊 Visualizations
- **Churn Distribution**: Countplot of churned vs. non-churned customers.
- **Confusion Matrix**: Displays model performance.
- **ROC Curve**: Evaluates the trade-off between sensitivity and specificity.

## 📦 Installation & Usage
Clone the repository and install dependencies:
```sh
 git clone https://github.com/Aduobey/Telco-Churn-Prediction.git
 cd Telco-Churn-Prediction
 pip install -r requirements.txt
```
Run the model script:
```sh
 python churn_model.py
```

## 📧 Contact
For questions or contributions, reach out via GitHub Issues.

---
