# 🩺 **Breast Cancer Prediction (ML Models)**

This project applies **multiple machine learning algorithms** to predict whether a breast tumor is **benign** or **malignant** based on nine medical features.

## 📊 **Features Used**

- Clump Thickness  
- Uniformity of Cell Size  
- Uniformity of Cell Shape  
- Marginal Adhesion  
- Single Epithelial Cell Size  
- Bare Nuclei  
- Bland Chromatin  
- Normal Nucleoli  
- Mitoses

**Target:** Class (2 = Benign, 4 = Malignant)

📌 **Dataset Source**: [UCI ML Repo](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Original))

## 🚀 **Steps**

1. Load and preprocess the dataset  
2. Apply feature scaling  
3. Train and evaluate multiple classification models:  
   - Logistic Regression  
   - Naive Bayes  
   - Support Vector Machine (SVM)  
   - Kernel SVM  
   - Decision Tree  
   - Random Forest  
   - K-Nearest Neighbors (KNN)  
4. Evaluate models using **confusion matrix** and **accuracy score**

## 📊 **Model Comparison**

| **Model**               | **Accuracy (%)** | **TN (Benign)** | **FP** | **FN** | **TP (Malignant)** |
|-------------------------|------------------|-----------------|--------|--------|--------------------|
| **Decision Tree**        | **95.9**         | 103             | 4      | 3      | 61                 |
| **Logistic Regression**  | **95.6**         | 84              | 3      | 3      | 47                 |
| **Kernel SVM**           | **95.3**         | 102             | 5      | 3      | 61                 |
| **K-Nearest Neighbors**  | **94.7**         | 103             | 4      | 5      | 59                 |
| **Naive Bayes**          | **94.1**         | 99              | 8      | 2      | 62                 |
| **Support Vector Machine**| **94.1**        | 102             | 5      | 5      | 59                 |
| **Random Forest**        | **93.6**         | 102             | 5      | 6      | 58                 |

## 🧾 **Confusion Matrix Terms Explained**

| **Term** | **Full Form**    | **What it Means**                                                             |
|----------|------------------|-------------------------------------------------------------------------------|
| **TP**   | True Positive     | Tumor is **malignant**, and the model **correctly** predicted malignant ✅      |
| **TN**   | True Negative     | Tumor is **benign**, and the model **correctly** predicted benign ✅            |
| **FP**   | False Positive    | Tumor is **benign**, but the model **wrongly** predicted malignant ❌          |
| **FN**   | False Negative    | Tumor is **malignant**, but the model **wrongly** predicted benign ❌          |

## 🧠 **Tools**

- Python (pandas, numpy, matplotlib, seaborn, sklearn)
- Google Colab / Jupyter Notebook

## ✅ **Outcome**

Each model is evaluated for accuracy and performance using confusion matrices. **Decision Tree**, **Logistic Regression**, and **Kernel SVM** showed the best results in predicting breast cancer outcomes.

