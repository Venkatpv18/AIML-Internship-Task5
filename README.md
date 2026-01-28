# Task 5: Train-Test Split & Evaluation Metrics

## Objective
The goal of this task is to understand how to:
- Split a dataset into training and testing sets
- Train a machine learning model
- Evaluate the model using standard performance metrics

This task focuses on **model evaluation fundamentals** using **Logistic Regression**.

---

## 🛠 Tools & Libraries Used
- Python
- Pandas
- Scikit-learn

---

## Dataset
Since file upload and internet access were restricted in the environment, a **built-in dataset from Scikit-learn** was used:

- **Breast Cancer Dataset (`load_breast_cancer`)**
- Binary classification problem
- Suitable for demonstrating train-test split and evaluation metrics

> Note: The same workflow applies to the Heart Disease dataset mentioned in the task.

---

## Steps Performed

###  Load Dataset
The dataset is loaded directly using Scikit-learn to avoid file and network issues.

### Train-Test Split
- The data is split into **80% training** and **20% testing**
- This helps evaluate model performance on unseen data

###  Model Training
- A **Logistic Regression** model is trained on the training data

###  Prediction
- Predictions are made on the test dataset

###  Evaluation Metrics
The following metrics are calculated:
- **Accuracy**
- **Precision**
- **Recall**
- **Confusion Matrix**
- **Classification Report**

---

##  Evaluation Metrics Explanation

- **Accuracy**: Overall correctness of the model  
- **Precision**: How many predicted positives are actually positive  
- **Recall**: How many actual positives were correctly identified  
- **Confusion Matrix**: Shows True Positives, True Negatives, False Positives, False Negatives  

---

## Results Interpretation
The model achieves good accuracy and balanced precision and recall, indicating that Logistic Regression performs well for binary classification problems on structured medical data.

## Conclusion
This task helped build a strong understanding of:
- Train-test splitting
- Logistic Regression
- Model evaluation metrics

These concepts are fundamental for building reliable machine learning models.
