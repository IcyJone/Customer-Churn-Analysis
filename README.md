# Customer Churn Prediction

This project develops a machine learning pipeline to identify high-risk customers for a telecommunications provider. Instead of chasing raw accuracy alone, it prioritizes **model interpretability** and **actionable business insights** so retention teams can intervene before customers leave.

---

## 📊 Dataset

The project uses the **Telco Customer Churn** dataset from Kaggle.

Source: Kaggle – Telco Customer Churn
Link: [https://www.kaggle.com/datasets/blastchar/telco-customer-churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

> **Note:** Download the dataset from Kaggle and place it in the project root directory.

---

## 🛠️ Installation & Usage

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/Customer-Churn-Analysis.git
   cd Customer-Churn-Analysis
   ```

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the analysis**
   Open `customer-churn.ipynb` (or the main notebook file) in Jupyter Notebook or VS Code and run all cells.

---

## 📈 Results

* **Model Performance**
  Achieved an ROC-AUC score of **~0.83** using Logistic Regression.

* **Key Insights**
   - Month-to-month contracts significantly increase churn probability.
   - Fiber Optic internet service customers show higher churn risk.
   - Longer tenure strongly reduces churn likelihood.
* **Business Outcome**
  Successfully segmented **~493 high-risk customers** for targeted retention campaigns.

---
