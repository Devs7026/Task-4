#  Logistic Regression

This repository contains code and instructions for **Task 4**: building and evaluating a logistic regression model to classify breast cancer tumors as malignant or benign using the Breast Cancer Wisconsin dataset.

---

## Steps Performed to Solve the Task: 

### 1. Data Loading and Cleaning
- Load the dataset using pandas.
- Remove unnecessary columns such as `id` and any empty columns (e.g., `Unnamed:32`).
- Convert the `diagnosis` column to binary (Malignant = 1, Benign = 0).

### 2. Data Preprocessing
- Split the data into features (`X`) and target (`y`).
- Perform a train-test split (e.g., 80% train, 20% test).
- Standardize features using `StandardScaler`.

### 3. Model Training
- Train a logistic regression model on the training data.

### 4. Model Evaluation
- Predict probabilities and classes on the test set.
- Compute evaluation metrics:
  - Confusion matrix
  - Classification report (precision, recall, F1-score, accuracy)
  - ROC curve and AUC
  - Precision-Recall curve

### 5. Visualization
- Plot the sigmoid function.
- Plot the ROC curve and Precision-Recall curve.

### 6. Threshold Tuning
- Demonstrate changing the decision threshold (e.g., from 0.5 to 0.3) and observe the impact on metrics.

---

## Results

- **High accuracy and AUC** are achievable with logistic regression on this dataset.
- **Visualizations** help interpret model performance and threshold effects.

---
