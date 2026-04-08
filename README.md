# Telco Customer Churn Prediction using SVM

This project predicts whether a telecom customer is likely to **churn (leave the service)** using a **Support Vector Machine (SVM)** machine learning model.

The workflow includes complete data preprocessing and model building steps such as:

* handling missing values
* converting categorical features into numerical format
* feature selection and cleaning
* balancing imbalanced classes using **SMOTE**
* feature normalization using **StandardScaler**
* training an **SVM classifier with RBF kernel**
* evaluating model performance using:

  * confusion matrix
  * classification report
  * accuracy score

The model is trained on the **Telco Customer Churn dataset** and aims to help telecom companies identify customers at high risk of leaving, enabling proactive retention strategies.

### Technologies Used

* Python
* Pandas
* Scikit-learn
* Imbalanced-learn (SMOTE)
* Google Colab / Jupyter Notebook

### ML Workflow

Data Loading → Preprocessing → Encoding → SMOTE → Train-Test Split → Scaling → SVM Training → Prediction → Evaluation
