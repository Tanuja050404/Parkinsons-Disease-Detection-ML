# Predictive Analytics for Parkinson’s Disease Progression

## 📌 Project Overview
This project uses **machine learning techniques** to detect Parkinson’s Disease based on biomedical voice measurements.  
The goal is to build a predictive model that can assist in **early diagnosis** and help track **disease progression**.

## 🔬 Dataset
- **File**: `Parkinsson disease.csv`
- **Description**: Contains biomedical voice measurements of patients.
- **Target Column**: `status`
  - `1` → Parkinson's positive  
  - `0` → Healthy  


## ⚙️ Approach
1. **Data Preprocessing**
   - Missing value check, scaling, and feature selection
2. **Model Selection**
   - Tested multiple algorithms (Logistic Regression, Random Forest, SVM, XGBoost)
   - Chose **XGBoost** for best performance
3. **Evaluation**
   - Accuracy, Precision, Recall, F1-score
   - ROC-AUC curve and Confusion Matrix
4. **Feature Importance**
   - Identified which voice features are most predictive

## 📊 Results
- Best Model: **XGBoost Classifier**
- Accuracy: 94.87% 

## 📈 Key Insights
- Certain frequency-based features had higher predictive power.
- Model shows potential for **clinical decision support**, though dataset is limited.

## 🚀 Future Work
- Explore deep learning approaches
- Add cross-validation and hyperparameter tuning
- Test on larger datasets for generalization

## 🛠️ Tech Stack
- Python (Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn)
- Jupyter Notebook
