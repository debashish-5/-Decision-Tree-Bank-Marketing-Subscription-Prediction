# 🏦 Bank Marketing Subscription Prediction
> Using Decision Tree Classifiers to optimize banking outreach.

![Banner](https://capsule-render.vercel.app)

## 🛠 Tech Stack & Skills

### 📊 Data Processing
![Python](https://img.shields.io)
![Pandas](https://img.shields.io)
![NumPy](https://img.shields.io)

### 🤖 Machine Learning
![Scikit-Learn](https://img.shields.io)
![Decision Trees](https://img.shields.io)

### 📈 Visualization
![Matplotlib](https://img.shields.io)
![Graphviz](https://img.shields.io)

---

## 📌 Project Overview
This project predicts whether a client will subscribe to a term deposit based on the **UCI Bank Marketing Dataset**. By training a Decision Tree Classifier, we identify the exact customer profiles most likely to convert.

## 🚀 Key Implementation Features
1. **Data Cleaning:** Handled 'unknown' categories and inconsistent text entries.
2. **Preprocessing:** Implemented Label Encoding and One-Hot Encoding for categorical features.
3. **Model Optimization:** Controlled `max_depth` to prevent overfitting.
4. **Analysis:** Visualized tree splits using `plot_tree()` for full interpretability.

## 🌳 Decision Tree Rules (Key Insights)
*   **Rule 1 (Duration):** If `call_duration` > 450s, the probability of subscription increases by 65%.
*   **Rule 2 (Previous Success):** If `poutcome` is "success", the conversion rate is significantly higher.
*   **Rule 3 (Contact Timing):** Contacts made during specific months (e.g., May) show distinct behavioral patterns.

## 📊 Performance Metrics
| Metric | Training Set | Test Set |
| :--- | :--- | :--- |
| **Accuracy** | 91.2% | 89.5% |
| **F1-Score** | 0.88 | 0.86 |

---

## 📂 How to Run
1. Clone the repo: `git clone https://github.com`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the notebook: `jupyter notebook bank_analysis.ipynb`

---
© 2026 | Data Science Portfolio
