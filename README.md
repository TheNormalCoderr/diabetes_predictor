# Diabetes Prediction Analysis

A data science project focused on exploring, analyzing, and building predictive models for diabetes risk classification.

## 📋 Project Overview

This project uses a health dataset to understand the relationship between health metrics (such as Glucose, BMI, and Age) and diabetes outcomes. The project explores the data through statistical correlation and develops machine learning models to predict the likelihood of diabetes.

## 🛠 Features

* **Data Exploration**: Uses `seaborn` and `matplotlib` to visualize relationships between features.


* **Data Cleaning**: Includes logic to handle missing values (indicated by 0s) and outlier analysis using the Interquartile Range (IQR).


* **Feature Analysis**: Uses correlation heatmaps to identify the most significant indicators for diabetes.


* **Modeling**: Uses `lazypredict` to benchmark various machine learning models to find the best-performing algorithm.



## 📊 Dataset Features

The dataset contains the following attributes:

* **Pregnancies**: Number of times pregnant.
* **Glucose**: Plasma glucose concentration.
* **BloodPressure**: Diastolic blood pressure.
* **SkinThickness**: Triceps skin fold thickness.
* **Insulin**: 2-Hour serum insulin.
* **BMI**: Body mass index.
* **DiabetesPedigreeFunction**: Diabetes pedigree function.
* **Age**: Patient age.
* **Outcome**: Target variable (1 for diabetes, 0 for no diabetes).

## 🚀 How to Run

1. **Clone the repository**:
```
git clone https://github.com/your-username/your-repo-name.git

```
2. **Install dependencies**:
```
pip install pandas numpy seaborn matplotlib scikit-learn lazypredict

```
3. **Run the Notebook**:
Open `diabetes-predictor.ipynb` in Jupyter Notebook or VS Code to perform the analysis.

BY -  Amiteshwar Singh
