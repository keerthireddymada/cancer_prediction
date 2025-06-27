# Logistic Regression Binary Classifier

This project builds a binary classifier using **Logistic Regression**, following the steps shown in the task instructions.

---

## Objective

- Build a binary classifier using logistic regression.
- Evaluate model performance with various metrics.
- Experiment with decision thresholds.

---

## Tools Used

- Python
- scikit-learn
- pandas
- matplotlib

---

## Steps

### 1. Load Dataset

- Used a binary classification dataset (e.g. Breast Cancer Wisconsin).
- Checked and cleaned data:
  - Removed null values.
  - Handled categorical columns if any.

---

### 2. Preprocessing

- Split data into training and test sets using `train_test_split`.
- Standardized features to have zero mean and unit variance.

---

### 3. Train Logistic Regression Model

- Fitted the logistic regression model on the training set.

---

### 4. Evaluate Model

- Evaluated performance using:
  - **Confusion Matrix**
  - **Precision**
  - **Recall**
  - **ROC-AUC score**

---

### 5. Tune Threshold

- Investigated how changing the classification threshold affects precision and recall.
- Plotted Precision-Recall curves.
- Adjusted threshold to prioritize true positives.

---

### 6. Sigmoid Function Explanation

- Explained how logistic regression uses the sigmoid function:

  \[
  \text{sigmoid}(z) = \frac{1}{1 + e^{-z}}
  \]

- Showed how the model’s linear output (z) transforms into predicted probabilities.
- Plotted sigmoid curve using real model outputs (`decision_function`).

---

## Notes

- Default classification threshold is **0.5**.
- Lowering the threshold can increase recall but may reduce precision.
- ROC-AUC helps measure model quality independent of the threshold.

---

**This completes the binary classification pipeline using Logistic Regression.**

