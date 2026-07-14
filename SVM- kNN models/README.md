## Author

**Nida Noor**

PKCERT AI and Software Development Internee

# Diabetes Prediction using Support Vector Machine (SVM) and k-Nearest Neighbors (kNN)

## Overview

This project predicts whether a patient has diabetes using two supervised machine learning classification algorithms:

- Support Vector Machine (SVM)
- k-Nearest Neighbors (kNN)

The models are trained and evaluated using the **Pima Indians Diabetes Dataset**.

---

## Dataset

The dataset used is **diabetes.csv**.

### Features

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

### Target

- Outcome
  - 0 = Non-Diabetic
  - 1 = Diabetic

---

## Data Preprocessing

The following preprocessing steps were performed:

- Loaded the dataset
- Handled missing values
- Replaced invalid zero values with median values
- Standardized numerical features using StandardScaler
- Split the dataset into training and testing sets (80:20)

---

## Models Implemented

- Support Vector Machine (SVM) with RBF Kernel
- k-Nearest Neighbors (kNN)

---

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report
- Confusion Matrix

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Project Structure

```
├── Task 9-SVM-kNN.ipynb
├── diabetes.csv
├── README.md
├── Summary_Report.pdf
```

---

## Results

| Model | Accuracy | Precision | Recall | F1-Score |
| SVM   | 74.68%   | 66.67%    | 58.18% | 62.14%   |
| kNN   | 73.38%   | 61.29%    | 69.09% | 64.96%   |
 
SVM achieved the highest overall accuracy and precision, while kNN produced better recall and F1-score.

---

## Recommended Model

Support Vector Machine (SVM) is recommended because it achieved the highest overall accuracy and precision on the diabetes dataset.

---


