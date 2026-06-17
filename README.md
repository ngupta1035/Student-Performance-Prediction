# Student Academic Performance Prediction using Machine Learning

## Project Overview

This project predicts students' final academic performance using Machine Learning techniques. The model is trained on the Student Performance Dataset and analyzes various factors such as demographics, family background, study habits, absences, and previous academic records to estimate the final grade.

The project demonstrates the complete Machine Learning workflow including data preprocessing, exploratory data analysis (EDA), model training, evaluation, feature importance analysis, and model deployment preparation.

---

## Dataset

Dataset: Student Performance Dataset

Target Variable:
- G3 (Final Grade)

Key Features:
- Study Time
- Absences
- Family Educational Support
- Internet Access
- Extra Educational Activities
- Previous Grades (G1, G2)
- Demographic Information

Dataset Size:
- 649 Records
- 33 Features

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Joblib

---

## Machine Learning Models

### 1. Linear Regression
A statistical model used to establish the relationship between features and the target variable.

### 2. Random Forest Regressor
An ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy.

---

## Workflow

1. Data Loading
2. Data Exploration
3. Missing Value Analysis
4. Data Visualization
5. Categorical Data Encoding
6. Feature Selection
7. Train-Test Split
8. Model Training
9. Model Evaluation
10. Feature Importance Analysis
11. Model Saving

---

## Exploratory Data Analysis

The following analyses were performed:

- Dataset Summary
- Statistical Analysis
- Missing Value Check
- Grade Distribution Visualization
- Correlation Heatmap
- Feature Importance Visualization

---

## Model Performance

| Model | MAE | RMSE | R² Score |
|---------|---------|---------|---------|
| Linear Regression | 0.765 | 1.215 | 0.849 |
| Random Forest | 0.737 | 1.236 | 0.843 |

### Cross Validation Score

Average R² Score: 0.780

---

## Important Features

The Random Forest model identified the following influential factors:

- G2 (Second Period Grade)
- Absences
- G1 (First Period Grade)
- Study Time
- Family Support

These features contribute significantly to predicting the final student grade.

---

## Project Structure

Student-Performance-Prediction/

├── Student_Performance.ipynb

├── student-por.csv

├── student_performance_model.pkl

├── requirements.txt

├── README.md

└── images/

    ├── grade_distribution.png
    
    ├── heatmap.png
    
    └── feature_importance.png

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Student-Performance-Prediction.git
```

Move into the project directory:

```bash
cd Student-Performance-Prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Running the Project

Open Jupyter Notebook:

```bash
jupyter notebook
```

Run:

```text
Student_Performance.ipynb
```

---

## Future Improvements

- Hyperparameter Tuning
- XGBoost Implementation
- Student Performance Classification
- Web-Based Prediction Interface
- Advanced Feature Engineering

---

## Author

Narayani Gupta

Bachelor of Engineering in Artificial Intelligence and Data Science
