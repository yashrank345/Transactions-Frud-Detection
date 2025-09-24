# Fraud Detection

## 📌 Overview
This project focuses on **Fraud Detection** using machine learning.  
The goal is to identify fraudulent transactions from a dataset by analyzing transaction patterns and applying classification models.

---

## 🛠️ Features
- Data preprocessing and cleaning  
- Exploratory Data Analysis (EDA)  
- Feature engineering and selection  
- Machine learning model training (e.g., Logistic Regression, Random Forest, XGBoost, etc.)  
- Model evaluation using metrics like **Accuracy, Precision, Recall, F1-score, and ROC-AUC**  
- Visualization of results  

---


---

## 📊 Dataset
The dataset contains financial transaction records with labels indicating whether the transaction is **fraudulent** or **legitimate**.  

**Typical columns include:**  
- `Time`  
- `Amount`  
- `Features`  
- `Class` (0 = Non-Fraud, 1 = Fraud)  

> ⚠️ Update this section with the actual dataset source (e.g., [Kaggle Credit Card Fraud Detection dataset](https://drive.usercontent.google.com/download?id=1VNpyNkGxHdskfdTNRSjjyNa5qC9u0JyV&export=download&authuser=0)).

---

## ⚙️ Installation
Clone this repository and install dependencies:

```bash
git clone https://github.com/yourusername/fraud-detection.git
cd fraud-detection
pip install -r requirements.txt
```

---

## ▶️ Usage

### 1. Run the Jupyter Notebook
Launch Jupyter Notebook and open the project file:

```bash
jupyter notebook "Frud Detection.ipynb"
```

## 📈 Results

- Fraudulent transactions were successfully identified with **high recall and precision**.  
- Multiple models were trained and compared.  
- The best-performing model was evaluated using **ROC-AUC**, which is suitable for imbalanced datasets.  

### 🔎 Evaluation Metrics
- **Accuracy**: Measures overall correctness.  
- **Precision**: Measures how many predicted frauds were actually fraud.  
- **Recall (Sensitivity)**: Measures how many actual frauds were detected.  
- **F1-Score**: Balance between precision and recall.  
- **ROC-AUC**: Captures model performance across all thresholds.  

### 📊 Visualizations
- **Confusion Matrix** – to show classification performance.  
- **ROC Curve** – to illustrate trade-offs between true positive and false positive rates.  
- **Precision-Recall Curve** – useful for imbalanced data.  



