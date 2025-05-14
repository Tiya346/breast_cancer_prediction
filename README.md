🩺 Breast Cancer Prediction (ML Models)
This project applies multiple machine learning algorithms to predict whether a breast tumor is benign (not cancerous) or malignant(cancerous) based on nine medical features.

📊 Features Used
Clump Thickness

Uniformity of Cell Size

Uniformity of Cell Shape

Marginal Adhesion

Single Epithelial Cell Size

Bare Nuclei

Bland Chromatin

Normal Nucleoli

Mitoses

Target: Class (2 = Benign, 4 = Malignant)

📌 Dataset Source: UCI ML Repo

🚀 Steps
Load and preprocess the dataset

Apply feature scaling

Train and evaluate multiple classification models:

Logistic Regression

Naive Bayes

Support Vector Machine (SVM)

Kernel SVM

Decision Tree

Random Forest

K-Nearest Neighbors (KNN)

Evaluate models using confusion matrix and accuracy score

📊 Model Comparison
Model	Accuracy (%)	TN	FP	FN	TP
Decision Tree	95.9	103	4	3	61
Logistic Regression	95.6	84	3	3	47
Kernel SVM	95.3	102	5	3	61
K-Nearest Neighbors	94.7	103	4	5	59
Naive Bayes	94.1	99	8	2	62
Support Vector Machine	94.1	102	5	5	59
Random Forest	93.6	102	5	6	58

🧠 Tools
Python (pandas, numpy, matplotlib, sklearn)
Google Colab / Jupyter Notebook

✅ Outcome
Each model is evaluated for accuracy and performance using confusion matrices. Decision Tree, Logistic Regression, and Kernel SVM showed the best results in predicting breast cancer outcomes.
