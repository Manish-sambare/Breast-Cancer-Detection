# Breast-Cancer-Prediction
 Built a binary classifier using SGD to differentiate between malignant and benign tumors, achieving 92% accuracy.

Breast Cancer Detection 🩺
Project Overview
This project focuses on building a binary classification model to detect breast cancer using the Wisconsin Breast Cancer dataset. The goal is to classify tumors as either malignant or benign using a Stochastic Gradient Descent (SGD) Classifier.

Dataset
Source: Wisconsin Breast Cancer Dataset
Features: 30 numeric features representing cell characteristics.
Target: Diagnosis label (M for Malignant and B for Benign).
Workflow
Data Preprocessing:

Dropped unnecessary columns.
Mapped categorical values to numerical labels.
Normalized the feature values for consistent input to the model.
Model Training:

Utilized SGD Classifier for binary classification.
Trained and validated the model using an 80-20 train-test split.
Evaluation:

Achieved an accuracy of 92%.
Evaluated using precision, recall, confusion matrix, and classification report.
Key Libraries Used
pandas, numpy
scikit-learn
How to Run
Install the required libraries:
bash
Copy code
pip install -r requirements.txt
Run the Jupyter notebook:
Open the Breast_Cancer.ipynb file and execute the cells sequentially.
Results
The model successfully classifies breast cancer cases with high accuracy, making it a promising approach for early-stage detection.

