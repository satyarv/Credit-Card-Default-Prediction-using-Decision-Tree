# Credit-Card-Default-Prediction-using-Decision-Tree
Developed a Decision Tree model to predict credit card default using client demographic and payment data from the UCI dataset. Achieved classification with a 6-level tree and evaluated using accuracy, confusion matrix, and feature importance visualization
# 💳 Credit Card Default Prediction using Decision Tree

This project builds a Decision Tree classifier to predict whether a customer will default on their credit card payment next month. It uses the well-known UCI dataset of Taiwanese credit card clients and explores feature importance and model evaluation metrics.

---

## 📊 Objective

To predict the likelihood of credit card default using customer demographics, credit limit, past payments, and bill statements.

---

## 🧰 Tools & Technologies

- Python (Google Colab)
- pandas, NumPy
- scikit-learn
- matplotlib

---

## 📂 Dataset

- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients)
- **File:** `default of credit card clients.xls`
- **Target Column:** `default payment next month` (renamed to `default`)

---

## 🛠️ Workflow

1. Loaded `.xls` file and renamed columns
2. Preprocessed data by removing `ID` column and splitting into features/target
3. Trained a Decision Tree with `max_depth=6`
4. Evaluated the model with:
   - Accuracy score
   - Confusion matrix
   - Classification report
5. Visualized:
   - Decision Tree
   - Feature importance

---

## 📈 Model Evaluation

- **Accuracy:** ~ (e.g., 81%) *(update with your actual result)*
- **Metrics Used:**
  - Confusion Matrix
  - Precision, Recall, F1-Score

---

## 🌳 Tree Visualization

The decision tree was visualized using `sklearn.tree.plot_tree()` to better understand the splits and logic behind predictions.

![Decision Tree](tree_visual.png) *(optional — upload image if needed)*

---

## 🔍 Feature Importance

A horizontal bar chart shows which features contributed most to the model’s prediction, such as `PAY_0`, `LIMIT_BAL`, and `BILL_AMT1`.
