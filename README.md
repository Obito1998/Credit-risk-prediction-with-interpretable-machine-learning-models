# redit-risk-prediction-with-interpretable-machine-learning-models-for-accuracy-and-transparency.
This project explores credit risk assessment using interpretable machine learning models. It compares simple models like logistic regression and SVM with more complex methods, while using explainability tools (like LIME) to balance accuracy with transparency.

📊 Evaluating Credit Risk Using Interpretable Machine Learning Models
📌 Overview

This project explores credit risk assessment using interpretable machine learning models. The goal is to design models that are not only accurate but also transparent enough for real-world financial decision-making and regulatory compliance.

We compare traditional models like Logistic Regression and Support Vector Machines (SVMs) with more advanced models like Random Forests, while using explainability frameworks (LIME) to interpret results.

🎯 Objectives

Evaluate simple and interpretable models for credit risk prediction.

Compare performance against more complex models.

Use LIME to make black-box models more explainable.

Balance predictive accuracy with model transparency for practical use in finance.

📂 Dataset

We used the Credit Risk Dataset from Kaggle:
👉 Credit Risk Dataset

Size: 1000 records

Features: 21 (categorical + numerical)

Target: Good credit (70%) vs Bad credit (30%)

⚙️ Methodology

Data Preprocessing

Handling missing values

Encoding categorical features

Feature importance selection

Models Tested

Logistic Regression

Support Vector Machines (Linear & Gaussian)

Random Forest (as a black-box model)

Evaluation Metrics

Accuracy

Recall

F1-score

Explainability

Applied LIME (Locally Interpretable Model-Agnostic Explanations) to improve interpretability of Random Forest outputs.

📈 Results
Model	Accuracy	Recall	F1-Score	Notes
Logistic Regression	71%	71%	69%	Simple, transparent
SVM (Gaussian Kernel)	72%	72%	69%	Best performing interpretable model
Random Forest	76%	76%	76%	Highest accuracy but less interpretable

Takeaway: Logistic Regression and SVM are more transparent but slightly less accurate. Random Forest performs better but needs tools like LIME for interpretability.
