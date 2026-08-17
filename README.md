# 🚢 Titanic Survival Prediction using Decision Tree

## 📌 Project Overview

This project uses the **Titanic dataset** to predict whether a passenger survived the Titanic disaster using a **Decision Tree Classifier**.

The project covers the complete machine learning workflow, including data cleaning, exploratory data analysis, preprocessing, model training, evaluation, and hyperparameter experimentation.

## 🎯 Objective

The main objective is to build a machine learning model that predicts passenger survival based on features such as:

* Passenger class
* Sex
* Age
* Number of siblings/spouses aboard
* Number of parents/children aboard
* Fare
* Port of embarkation

## 📊 Dataset

The Titanic dataset contains information about passengers aboard the Titanic.

**Target Variable:**

* `survived`

  * `0` → Did not survive
  * `1` → Survived

### Features Used

| Feature    | Description                       |
| ---------- | --------------------------------- |
| `pclass`   | Passenger class                   |
| `sex`      | Passenger gender                  |
| `age`      | Passenger age                     |
| `sibsp`    | Number of siblings/spouses aboard |
| `parch`    | Number of parents/children aboard |
| `fare`     | Passenger fare                    |
| `embarked` | Port of embarkation               |

## 🔍 Exploratory Data Analysis

The following visualizations were used to understand the dataset:

* Survival distribution
* Survival by gender
* Survival by passenger class
* Age distribution
* Fare distribution
* Correlation matrix
* Outlier analysis

## 🧹 Data Preprocessing

The following preprocessing steps were performed:

1. Selected relevant features.
2. Checked for missing values.
3. Filled missing numerical values using the median.
4. Filled missing categorical values using the mode.
5. Converted categorical variables into numerical values using one-hot encoding.
6. Split the dataset into training and testing sets.

## 🌳 Machine Learning Model

### Decision Tree Classifier

A Decision Tree Classifier was used for prediction.

Two splitting criteria were explored:

* **Gini Impurity**
* **Entropy**

The model was also tested with different `max_depth` values to study and control overfitting.

## 📈 Model Evaluation

The model was evaluated using:

* Accuracy
* F1-score
* Confusion Matrix

Training and testing accuracy were also compared to identify potential overfitting.

## 📊 Visualizations

### Exploratory Data Analysis




* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
*Google colab

## 📁 Project Structure

```text
Titanic-Decision-Tree/
│
├── Titanic_Decision_Tree.ipynb
├── README.md
│
└── images/
    ├── eda.png
    ├── correlation.png
    ├── model_performance.png
    ├── confusion_matrix.png
    └── feature_importance.png
```

## 💡 Key Learnings

Through this project, I learned:

* How to perform EDA on a real-world dataset
* How to handle missing values
* How to encode categorical variables
* How Decision Trees make predictions
* Difference between Gini Impurity and Entropy
* How Decision Trees can overfit
* How `max_depth` helps control model complexity
* How to evaluate a classification model
* How to analyze feature importance



This project was created as part of my machine learning learning journey.
