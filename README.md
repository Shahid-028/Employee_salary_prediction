# 🧠 Employee Salary Prediction Project

This project focuses on building a machine learning model to predict whether an individual's annual income exceeds \$50K, based on demographic and employment-related attributes from census data.

## 🎯 Objective

Develop a predictive model using supervised machine learning algorithms to classify individuals as earning **>50K** or **≤50K** per year.

## 📊 Dataset

* **Source**: [UCI Machine Learning Repository – Adult Dataset](https://archive.ics.uci.edu/ml/datasets/adult)
* **Filename**: `adult 3.csv`

### 🔑 Features Used:

* Age
* Workclass
* Education
* Marital-status
* Occupation
* Relationship
* Race
* Sex
* Hours-per-week
* Native-country
* **Income** *(Target: >50K or <=50K)*

## 🧰 Tools & Libraries

* **Language**: Python 3.x
* **Libraries**:

  * Data manipulation: `pandas`, `numpy`
  * Visualization: `matplotlib`, `seaborn`
  * Modeling: `scikit-learn`
* **Environment**: Jupyter Notebook

## ⚙️ Project Workflow

### 1. **Data Preprocessing**

* Handle missing values
* Encode categorical variables using label encoding or one-hot encoding
* Train-test split (e.g., 80/20)

### 2. **Exploratory Data Analysis (EDA)**

* Visualize distributions and relationships
* Correlation heatmaps and feature analysis
* Identify trends and outliers

### 3. **Modeling**

Implemented and evaluated the following classifiers:

* Logistic Regression
* Decision Tree
* Random Forest
* Support Vector Machine (SVM)
* Gradient Boosting (Best Performing)

### 4. **Evaluation Metrics**

* Accuracy
* Precision
* Recall
* F1-Score

## 📈 Results

> ✅ **Best Model**: **Gradient Boosting**
> 📊 **Accuracy Achieved**: **85.71%**

Gradient Boosting outperformed other models in terms of both accuracy and generalization.

## 🚀 How to Run the Project

1. Clone or download the repository
2. Ensure Python and Jupyter Notebook are installed
3. Install required libraries (e.g., `pip install -r requirements.txt`)
4. Open terminal and run:

```bash
jupyter notebook Employee_Salary_Prediction.ipynb
```

## 📝 Conclusion

* Gradient Boosting provided the most accurate predictions for income classification.
* Further improvements can be made by tuning hyperparameters or adding feature engineering.
