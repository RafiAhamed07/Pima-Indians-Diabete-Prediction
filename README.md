# Pima Indians Diabetes Prediction

## 📌 Overview
This project predicts the likelihood of diabetes in patients based on health-related attributes such as glucose level, BMI, blood pressure, and more.  
It uses the **Pima Indians Diabetes Dataset** and applies machine learning techniques to classify patients as diabetic or non-diabetic.

## 📂 Dataset
The dataset comes from the [UCI Machine Learning Repository](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database) and contains:
- **Pregnancies**: Number of pregnancies
- **Glucose**: Plasma glucose concentration
- **BloodPressure**: Diastolic blood pressure (mm Hg)
- **SkinThickness**: Triceps skinfold thickness (mm)
- **Insulin**: 2-Hour serum insulin (mu U/ml)
- **BMI**: Body mass index
- **DiabetesPedigreeFunction**: Diabetes pedigree function
- **Age**: Age in years
- **Outcome**: Class variable (0: non-diabetic, 1: diabetic)

## 🛠 Features
- Data cleaning & preprocessing (handling missing values, fixing outliers, scaling)
- Exploratory data analysis (EDA) with visualizations
- Machine learning model training (Logistic Regression, Random Forest, etc.)
- Model evaluation (accuracy, precision, recall, F1-score, ROC curve)
- Final predictions on test data

## 📊 Machine Learning Workflow
1. **Data Loading** – Import dataset and explore its structure.
2. **Data Cleaning** – Handle missing values, remove/fix outliers.
3. **Feature Engineering** – Scale numerical features, select important predictors.
4. **Model Training** – Train classification models.
5. **Evaluation** – Compare models and select the best-performing one.
6. **Prediction** – Use the model for predicting diabetes risk.


🚀 Usage
Clone this repository:

```bash

git clone https://github.com/RafiAhamed07/Pima-Indians-Diabete-Prediction.git
cd Pima-Indians-Diabete-Prediction
```


## 📦 Requirements
Install dependencies using:
```bash
pip install -r requirements.txt
```

Run the notebook:

```bash

jupyter notebook "Pima Indians Diabetes Prediction.ipynb"

```


📜 License
This project is licensed under the MIT License.

🙌 Acknowledgments

    1. UCI Machine Learning Repository

    2. Kaggle Dataset