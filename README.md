# 🚀 Support Vector Machines (SVM) 

This project demonstrates how to use Support Vector Machines (SVM) for binary classification tasks, including both **linear** and **non-linear (RBF)** kernels. The project also includes decision boundary visualizations, hyperparameter tuning using GridSearchCV, and performance evaluation using cross-validation.

## 📌 Objective

To apply SVM for classifying user purchase behavior based on their Age and Estimated Salary using the **Social Network Ads** dataset.

## 📂 Dataset

- **Source:** [Kaggle - Social Network Ads](https://www.kaggle.com/datasets/rakeshrau/social-network-ads)
- **Features:**  
  - `Age` (numerical)  
  - `EstimatedSalary` (numerical)
- **Target:**  
  - `Purchased` (0 = No, 1 = Yes)

## 📊 Project Workflow

1. **Load and explore the dataset**
2. **Select relevant features and target**
3. **Split the data into training and testing sets**
4. **Scale the features using StandardScaler**
5. **Train SVM models with both Linear and RBF kernels**
6. **Visualize decision boundaries on the training set**
7. **Evaluate model performance on the test set**
8. **Tune hyperparameters (`C` and `gamma`) using GridSearchCV**
9. **Perform cross-validation for model reliability**
10. **Visualize the decision boundary of the best-tuned model**

## 📈 Results

- **Confusion Matrix**
- **Classification Report (Precision, Recall, F1-Score)**
- **Model Accuracy**
- **Best Hyperparameters via GridSearchCV**
- **Cross-Validation Accuracy**

## 📸 Sample Visualizations

- Decision boundary for Linear and RBF kernels
- Decision boundary for best-tuned SVM model
