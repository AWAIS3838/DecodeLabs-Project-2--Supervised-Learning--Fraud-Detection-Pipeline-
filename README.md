# DecodeLabs-Project-2--Supervised-Learning--Fraud-Detection-Pipeline-
# 🛡️ Credit Card Fraud Detection using Machine Learning

> Detect fraudulent credit card transactions using Machine Learning with SMOTE, Logistic Regression, and Random Forest.

---

## 📌 Table of Contents

- Project Overview
- Dataset
- Project Workflow
- Technologies Used
- Installation
- Usage
- Project Structure
- Exploratory Data Analysis
- Data Preprocessing
- Models Used
- Model Evaluation
- Results
- Future Improvements
- Author
- License

---

# 📖 Project Overview

Credit card fraud detection is a binary classification problem where the objective is to identify fraudulent transactions from legitimate ones. Since fraud transactions are extremely rare, this project applies SMOTE to handle class imbalance and evaluates models using Precision, Recall, F1-Score, and ROC-AUC.

---

# 📊 Dataset

- **Dataset:** Credit Card Fraud Detection
- **Rows:** 284,807
- **Features:** 30
- **Target:** `Class`
  - `0` → Legitimate Transaction
  - `1` → Fraudulent Transaction

---

# 🔄 Project Workflow

1. Load Dataset
2. Data Exploration
3. Data Cleaning
4. Exploratory Data Analysis (EDA)
5. Feature Scaling
6. Train-Test Split
7. Apply SMOTE
8. Train Logistic Regression
9. Train Random Forest
10. Hyperparameter Tuning
11. Model Evaluation
12. Model Comparison
13. Save Final Model

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Imbalanced-Learn
- Joblib

---

# ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/AWAIS3838/DecodeLabs-Project-2--Supervised-Learning--Fraud-Detection-Pipeline-.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# ▶️ Usage

Run the Jupyter Notebook:

```bash
jupyter notebook Fraud_Detection.ipynb
```

---

# 📂 Project Structure

```text
DecodeLabs-Project-2--Supervised-Learning--Fraud-Detection-Pipeline-/
│
├── data/
│   └── creditcard.csv
│
├── notebooks/
│   └── Fraud_Detection.ipynb
│
├── models/
│   └── fraud_detection_model.pkl
│
├── images/
│
├── README.md
│
└── requirements.txt
```

---

# 📈 Exploratory Data Analysis

- Class Distribution
- Transaction Amount Distribution
- Correlation Heatmap
- Fraud vs Normal Comparison

---

# ⚖️ Data Preprocessing

- Missing Value Check
- Duplicate Removal
- Feature Scaling
- Train-Test Split
- SMOTE

---

# 🤖 Models Used

- Logistic Regression
- Random Forest

---

# 📊 Model Evaluation

The models are evaluated using:

- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix

---

# 🏆 Results

| Model | Precision | Recall | F1-Score | ROC-AUC |
|--------|----------:|-------:|---------:|---------:|
| Logistic Regression | XX | XX | XX | XX |
| Random Forest | XX | XX | XX | XX |

> Replace `XX` with your final results after training.

---

# 🚀 Future Improvements

- XGBoost
- LightGBM
- CatBoost
- Model Deployment
- Real-Time Prediction API

---

# 👨‍💻 Author

**Awais Khatti**
Computer Science Student | AI Engineer | Data Science Enthusiast
