**🧬A Machine Learning approach for classifying breast cancer tumors as Malignant or Benign using supervised learning models**

**📌 Project Overview**

This project applies multiple machine learning algorithms to classify tumor cells based on diagnostic features. After comparative evaluation, Support Vector Machine (SVM) demonstrated the best performance in terms of accuracy, precision, recall and F1-score.

**📌 Why This Project**

Breast cancer remains one of the leading causes of cancer-related deaths worldwide. Early and accurate diagnosis significantly improves survival rates.

**🎯 Objectives**

Perform exploratory data analysis (EDA) and Principal Component Analysis(PCA)

Train multiple classification models

Compare performance across models

Validate robustness using 10-Fold Cross Validation

Evaluate using standard performance metrics

Identify the best-performing model

**🗂 Dataset**

This project uses the Breast Cancer Wisconsin Diagnostic Dataset. It consists of:

🔢 569 samples

📊 30 numerical tumor cell features

🎯 Binary classification

          Malignant=1(Positive)
          
          Benign=0 (Negative)

**🔬 Project Workflow**

**1️⃣ Data Preprocessing**

Checked missing values

Feature scaling using StandardScaler

Train-test split


**2️⃣ Model Training**

Trained and compared multiple classifiers:

Logistic Regression

K-Nearest Neighbors

Gradient Boosting

Random Forest

Support Vector Machine (SVM)

**4️⃣ Robust Validation for all ML models**

10-Fold Cross Validation

Performance comparison across folds

Overfitting check

**📈 Evaluation Metrics Used**

Accuracy

Precision

Recall

F1-Score

ROC-AUC Curve

Confusion Matrix (Best Scoring Model)

Cross-Validation Mean ± Standard Deviation (Best Scoring Model)

**🏆 Best Model: Support Vector Machine (SVM)**

**SVM achieved**:

Highest accuracy

Strong generalization performance

Stable cross-validation scores

**🔬 Validation Strategy**

**To ensure robustness**:

Train-Test Split

10-Fold Cross Validation

Performance comparison across different ML models

**🔬 Key Scientific Takeaways**

PCA visualization reveals that malignant samples are more widely distributed in principal component space as compared to benign samples. Appropriate feature scaling improved the performance of SVM towards classifying breast cancer data, yielding robust and generalizable predictive performance

**🛠 Tools used**

Python

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook
