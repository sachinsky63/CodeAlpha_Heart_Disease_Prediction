# ❤️ Heart Disease Prediction Using Machine Learning

## 📌 Project Overview

The **Heart Disease Prediction System** is a Machine Learning project that predicts the possibility of heart disease based on various medical attributes of a patient.

The project uses multiple Machine Learning classification algorithms to analyze patient data, train predictive models, and compare their performance using different evaluation metrics.


## 🎯 Objectives

- Analyze heart disease datasets using Exploratory Data Analysis (EDA).
- Perform data preprocessing and feature scaling.
- Build and train multiple Machine Learning classification models.
- Evaluate and compare model performance.
- Develop a predictive system using trained models.
- Deploy the prediction functionality using FastAPI.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn, XGBoost
- **Development Environment:** Jupyter Notebook, VS Code

## 📂 Machine Learning Algorithms

The following algorithms are implemented:

1. Logistic Regression
2. Naive Bayes
3. K-Nearest Neighbors (KNN)
4. Decision Tree Classifier
5. Support Vector Machine (SVM)
6. Random Forest Classifier
7. XGBoost Classifier

## 📊 Dataset Information

The project uses a Heart Disease dataset containing medical information about patients.

The dataset includes the following features:

| Feature | Description |
|---|---|
| age | Age of the patient |
| sex | Gender |
| cp | Chest pain type |
| trestbps | Resting blood pressure |
| chol | Serum cholesterol |
| fbs | Fasting blood sugar |
| restecg | Resting ECG results |
| thalach | Maximum heart rate achieved |
| exang | Exercise-induced angina |
| oldpeak | ST depression |
| slope | Slope of peak exercise ST segment |
| ca | Number of major vessels |
| thal | Thalassemia |
| target | Heart disease indicator |

**Target Variable:**
- 0 – No heart disease
- 1 – Heart disease

## ⚙️ Project Workflow

1. Import required libraries.
2. Load the heart disease dataset.
3. Perform data cleaning and preprocessing.
4. Conduct Exploratory Data Analysis.
5. Separate features and target variables.
6. Split the dataset into training and testing sets.
7. Apply feature scaling where required.
8. Train multiple classification algorithms.
9. Evaluate models using performance metrics.
10. Compare model performance.

## 📈 Model Evaluation

The models are evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

### Logistic Regression Results

| Metric | Score |
|---|---:|
| Accuracy | 88.50% |
| Precision | 85.19% |
| Recall | 75.41% |
| F1 Score | 80.00% |

*Other model performance results can be added after completing the comparison.*


### 1. Clone the Repository

```bash
git https://github.com/sachinsky63/CodeAlpha_Heart_Disease_Prediction.git
```

### 2. Navigate to Project Directory

```bash
cd Heart_Disease_Prediction
```

### 3. Create Virtual Environment

```bash
python -m venv venv
```

### 4. Activate Virtual Environment

Windows:

```bash
venv\Scripts\activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

### 6. Run Jupyter Notebook

```bash
jupyter notebook
```
## 👨‍💻 Author

**Sachin Kumar Yadav**