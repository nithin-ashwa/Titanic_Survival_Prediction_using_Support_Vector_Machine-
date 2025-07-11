# 🚢 Titanic Survival Prediction using Support Vector Machine (SVM)

This project builds a machine learning pipeline using Support Vector Machine (SVM) to predict passenger survival on the Titanic dataset. It includes preprocessing, feature engineering, and model evaluation using scikit-learn.

## 📂 Dataset

The dataset used is the classic [Titanic dataset](https://www.kaggle.com/c/titanic), which contains information about the passengers aboard the Titanic, such as age, sex, ticket class, and whether or not they survived.

## 🧰 Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Seaborn
- Matplotlib (optional for visualization)

## ⚙️ Features

- Preprocessing: 
  - Dropping irrelevant features (`Cabin`, `Name`, `Ticket`)
  - Filling missing values (mean for `Age`, mode for `Embarked`)
- One-hot encoding for categorical variables (`Sex`, `Embarked`)
- SVM classifier with RBF kernel
- Evaluation using accuracy score

## 📊 Model Pipeline

The pipeline includes:
- ColumnTransformer: Handles both numerical and categorical features
- SVC (Support Vector Classifier): RBF kernel with `C=1.0` and `gamma='scale'`

## 🧪 How to Run

1. Clone the repository
```bash
git clone https://github.com/your-username/titanic-svm.git
cd titanic-svm
