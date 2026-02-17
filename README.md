# Bank Marketing Prediction Analysis
**Project Objective**: Predict term deposit subscriptions using Decision Tree logic.

---

## Technical Stack

| Domain | Integrated Technologies |
| :--- | :--- |
| **Development** | ![Python](https://img.shields.io) |
| **Data Engine** | ![Pandas](https://img.shields.io) ![NumPy](https://img.shields.io) |
| **Modeling** | ![Scikit-Learn](https://img.shields.io) |
| **Visuals** | ![Matplotlib](https://img.shields.io) ![Graphviz](https://img.shields.io) |

---

## Executive Summary
This project utilizes the UCI Bank Marketing dataset to build a predictive model for financial products. The workflow involves categorical encoding, data splitting, and depth-limited tree induction to ensure model generalizability.

## Decision Logic (Key Rules)
1. **Duration Influence**: Last contact duration acts as the primary root split; values exceeding a specific threshold correlate strongly with successful conversion.
2. **Historical Performance**: Clients who previously subscribed to bank products exhibit a higher propensity for repeat conversion.
3. **Contact Timing**: Model splits indicate that the month and day of contact significantly impact the variance in success rates.

## Model Evaluation
* **Training Accuracy**: 91.4%
* **Testing Accuracy**: 89.2%
* **Regularization**: Max depth restricted to 5 levels to mitigate overfitting.

---
