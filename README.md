# Fraud-Detection-using-XGBoost
 A machine learning project to detect fraudulent credit card transactions. The pipeline covers data preprocessing, model training, hyperparameter tuning with GridSearchCV, evaluation (accuracy, F1, ROC AUC), and feature importance visualization.

---

## 📂 Project Structure
```
├── data/                # Dataset (not included in repo, add your dataset here)
├── main.py              # Main script for training & evaluation
├── requirements.txt     # List of dependencies
└── README.md            # Project description
```

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/fraud-detection-xgboost.git
   cd fraud-detection-xgboost
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Add your dataset (CSV format) into the `data/` folder.
4. Run the project:
   ```bash
   python main.py
   ```

---

## 📊 Model & Results
- Algorithm: **XGBoost Classifier**
- Tuned hyperparameters (via GridSearchCV)
- Train/Test split with stratification
- Balanced dataset: **50,000 fraud / 50,000 non-fraud**

**Performance (Test Set):**
- Accuracy: ~96%  
- ROC AUC: ~0.967  
- Precision & Recall balanced for both classes  

---

## 🔑 Key Features
- Preprocessing of categorical variables (`LabelEncoder`)
- XGBoost with hyperparameter tuning
- Performance metrics: Confusion Matrix, Classification Report, ROC AUC
- Feature importance visualization

---

## 📌 Next Steps
- Add comparison with Random Forest and Logistic Regression
- Threshold tuning for better recall on fraud detection
- Deploy model with **Streamlit** for interactive demo
