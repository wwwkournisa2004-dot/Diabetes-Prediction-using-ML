# Diabetes Prediction using Machine Learning

A machine learning project that predicts whether a person is likely to have diabetes based on health-related parameters. This project was developed to understand the complete machine learning workflow, including data preprocessing, model training, evaluation, and prediction using Python.

---

## Project Overview

Diabetes is one of the most common chronic diseases worldwide. Early prediction can help in timely diagnosis and better healthcare decisions. This project uses the Pima Indians Diabetes Dataset to build a classification model capable of predicting whether a person is diabetic based on medical information.

The project demonstrates the complete machine learning pipeline, making it suitable for beginners who want to learn practical implementation using Scikit-learn.

---

## Project Structure

```text
Diabetes-Prediction-using-ML/
│
├── Diabetes_Prediction_using_ML.ipynb
├── diabetes.csv
└── README.md
```

---

## Dataset

The dataset contains medical information collected from female patients.

### Features

* Pregnancies
* Glucose
* Blood Pressure
* Skin Thickness
* Insulin
* BMI (Body Mass Index)
* Diabetes Pedigree Function
* Age

### Target Variable

* 0 – Non-Diabetic
* 1 – Diabetic

---

## Technologies Used

* Python
* Jupyter Notebook
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

---

## Machine Learning Model

This project uses the Support Vector Machine (SVM) algorithm with a Linear Kernel for binary classification.

The workflow includes:

* Importing required libraries
* Loading the dataset
* Exploring the data
* Feature scaling using StandardScaler
* Splitting the dataset into training and testing sets
* Training the SVM model
* Evaluating model performance
* Predicting diabetes for new patient data

---

## How to Run the Project

### Clone the Repository

```bash
git clone https://github.com/wwwwkournisa2004-dot/Diabetes-Prediction-using-ML.git
```

### Install Required Libraries

```bash
pip install numpy pandas matplotlib scikit-learn jupyter
```

### Open the Notebook

```bash
jupyter notebook Diabetes_Prediction_using_ML.ipynb
```

Run all notebook cells sequentially to reproduce the results.

---

## Future Improvements

Possible enhancements include:

* Comparing multiple machine learning algorithms
* Hyperparameter tuning using GridSearchCV
* Confusion Matrix
* Precision, Recall, and F1-Score
* ROC Curve
* Cross-validation
* Deploying the model using Streamlit or Flask

---

## Learning Outcomes

This project helped me gain practical experience in:

* Data preprocessing
* Feature scaling
* Binary classification
* Machine learning model training
* Model evaluation
* Predictive analytics using Scikit-learn

---

## Author

**Nisa Kour**

BCA Student | Learning Machine Learning, Data Analytics, and AI

Passionate about building practical projects and continuously improving my skills in data science and artificial intelligence.

---

Thank you for visiting this repository. Feedback and suggestions are always appreciated.
