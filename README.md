# Credit Card Fraud Detection 🔍💳

A machine learning project to detect fraudulent credit card transactions and analyze the cost-benefit of model deployment for a financial services firm.

---

## 🧠 Objective

To build a fraud detection system using machine learning for **Finnex**, a US-based financial services company, with the goal of reducing fraud losses and improving customer trust. The project includes financial analysis to demonstrate the practical impact of deploying such a model.

---

## 📊 Dataset & Problem

- Highly imbalanced dataset: Only **0.57%** of transactions are fraudulent.
- Binary classification problem with `is_fraud` as the target variable.
- Features include transaction details, time, location, customer demographics.

---

## 🧪 Techniques Used

- **Random Forest Classifier**
- **ADASYN (Adaptive Synthetic Sampling)** to address class imbalance.
- Manual hyperparameter tuning.
- Evaluation using metrics such as **accuracy**, **precision**, **recall**, and **F1-score**.

---

## 🔍 Key Insights

- Fraudulent transactions are more common on **weekends** and **between 10 PM to 3 AM**.
- **Female customers** account for ~55% of total transactions and may be slightly more vulnerable.
- Fraud detection systems can be enhanced using a **second layer of authentication**.

---

## 💰 Cost-Benefit Analysis

We evaluated the cost impact of the model by comparing:

| Scenario | Formula |
|----------|---------|
| Before Model | `Average Fraud Amount * Avg. Monthly Fraud Count` |
| After Model  | `1.5 * True Positives + Average Fraud Amount * False Negatives` |

📈 **Significant savings** observed when the model is deployed.

Details: See `Cost_Benefit_Analysis.xlsx`

---

## 📁 Files

| File | Description |
|------|-------------|
| `Abhishek_Fraud_Detection_code.ipynb` | Jupyter Notebook with all preprocessing, model training, evaluation, and analysis |
| `Credit_Card_Fraud_Detection.pptx` | Executive presentation summarizing the project |
| `Cost_Benefit_Analysis.xlsx` | Excel sheet evaluating the financial benefit of deploying the fraud detection model |

---

## 📽️ Video Presentation

[Watch the 7-minute presentation](https://drive.google.com/file/d/1fWtVhJy3JfUQp4lJFzNKINXDVKNDf2P_/view)

---

## 🛠 Tech Stack

- Python
- Pandas, NumPy, Scikit-learn, Imbalanced-learn
- ADASYN
- Jupyter Notebook
- Excel, PowerPoint

---

## 👨‍💻 Author

**Abhishek Kunbhare**

---

## 📌 How to Use

1. Clone the repo:
   ```bash
   git clone https://github.com/abhishek010314/credit-card-fraud-detection.git
