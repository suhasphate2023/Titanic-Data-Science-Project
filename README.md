# Titanic-Data-Science-Project
A Data Science project using Python to analyze the Titanic dataset, perform data cleaning, exploratory data analysis, visualization, and machine learning for passenger survival prediction.
Titanic Survival Prediction – Week 3
Data Science with Python Internship
This project is part of Week 3 of my Data Science with Python internship.
Project Title
Titanic Survival Prediction
Objective
The objective of this project is to develop and evaluate machine learning classification models to predict whether a Titanic passenger survived or did not survive.
Dataset
The Titanic dataset contains passenger information including:
•	Passenger Class (Pclass)
•	Sex
•	Age
•	SibSp
•	Parch
•	Fare
•	Embarked
•	Survived
The dataset contains 891 observations and 12 variables.
Technologies Used
•	Python
•	Google Colab
•	Pandas
•	NumPy
•	Matplotlib
•	Scikit-learn
Machine Learning Models
The following classification algorithms were evaluated:
1.	Logistic Regression
2.	Decision Tree
3.	Random Forest
Model Evaluation
The Logistic Regression model was evaluated using:
•	Accuracy
•	Precision
•	Recall
•	F1-Score
•	Confusion Matrix
•	ROC Curve
•	ROC-AUC
•	5-Fold Cross-Validation
Results
Model / Metric	Result
Logistic Regression Accuracy	80.45%
Precision	79.31%
Recall	66.67%
F1-Score	72.44%
ROC-AUC	0.8433
5-Fold CV Mean Accuracy	79.12%
Decision Tree Accuracy	82.12%
Random Forest Accuracy	81.56%
Project Workflow
Dataset → Data Preprocessing → Feature Selection → Encoding → Train-Test Split → Model Training → Evaluation → Cross-Validation → Algorithm Comparison → Conclusion
Files
•	Week3_Titanic_Final_Report.docx – Final project report
•	Titanic_Week3_Model.ipynb – Python/Google Colab notebook
•	Titanic-Dataset(1).csv – Dataset
•	Confusion_Matrix.png – Confusion matrix visualization
•	ROC_Curve.png – ROC curve visualization
•	Algorithm_Comparison.png – Model comparison visualization
Conclusion
The project demonstrates the application of machine learning classification techniques to predict Titanic passenger survival. Logistic Regression achieved 80.45% test accuracy and an ROC-AUC of 0.8433. Decision Tree and Random Forest achieved test accuracies of 82.12% and 81.56%, respectively, on the selected test split.

# Week 4 – Data Visualization and Storytelling

## Project Overview

This project is completed as part of the Week 4 Data Visualization and Storytelling task. The project uses the Titanic dataset to demonstrate how Python-based data visualization can be used to explore data, identify patterns, and communicate meaningful insights.

## Objective

The main objectives of this project are:

* To explore the Titanic dataset.
* To create clear and informative visualizations.
* To compare survival patterns among passenger groups.
* To examine relationships between numerical variables.
* To develop a meaningful data story from the visual findings.
* To demonstrate how visualization can support data-driven decisions.

## Dataset

The project uses the Titanic dataset containing passenger information such as:

* Passenger Class
* Sex
* Age
* Fare
* Number of Siblings/Spouses
* Number of Parents/Children
* Survival Status

## Visualizations

The project includes three main visualizations:

1. **Bar Chart – Survival Rate by Passenger Class**

   * Compares survival rates among different passenger classes.

2. **Age Distribution Plot**

   * Shows the distribution of passenger ages according to survival status.

3. **Correlation Heat Map**

   * Shows relationships among selected numerical variables such as Age, Fare, Passenger Class, and Survival.

## Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook / Python IDE

## Project Structure

```text
week4-data-visualization-storytelling/
│
├── Titanic-Dataset.csv
├── Week_4_Data_Visualization_and_Storytelling_Titanic_Report.docx
├── 01_survival_by_class.png
├── 02_age_survival.png
├── 03_correlation_heatmap.png
├── titanic_visualization.py
└── README.md
```

## Key Findings

The visualizations show differences in survival rates across passenger classes, provide an overview of age distributions among survivors and non-survivors, and highlight relationships between selected numerical variables.

## Conclusion

This project demonstrates how data visualization can transform raw data into understandable information. Using multiple visualization techniques makes it easier to identify patterns and communicate findings to a non-technical audience.

## Author

**Suhas Phate**

# Week 5 – Model Evaluation and Optimization

## Project Title

Titanic Survival Prediction using Python

## Objective

The objective of this project is to evaluate and optimize a machine learning classification model for predicting passenger survival using the Titanic dataset.

## Model Used

* Logistic Regression
* GridSearchCV for hyperparameter optimization
* 5-Fold Stratified Cross-Validation

## Features Used

* Pclass
* Sex
* Age
* SibSp
* Parch
* Fare
* Embarked

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC
* Confusion Matrix
* ROC Curve
* Cross-Validation

## Results

| Metric    |  Score |
| --------- | -----: |
| Accuracy  | 80.45% |
| Precision | 79.31% |
| Recall    | 66.67% |
| F1-Score  | 72.44% |
| ROC-AUC   | 84.37% |

## Optimization

GridSearchCV was used to tune the Logistic Regression parameters.

Best parameters:

* C = 1
* Solver = liblinear

## Tools and Technologies

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## Project Report

The complete Week 5 internship report is available in this repository.












