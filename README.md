# Identifying High-Risk Patients for Targeted Prevention and Intervention

![patient-treatment-classification](https://github.com/MitaliP001/Identifying-High-Risk-Patients-for-Targeted-Prevention-and-Intervention/blob/main/assets/patient-treatment-classification.png)

Programming Tools : Python in Jupyter Notebook

## Problem Statement

The healthcare industry faces a growing need to identify high-risk patients who are more likely to develop medical complications. This project aims to address this challenge by leveraging data science and machine learning techniques to predict and target prevention and intervention efforts effectively. Our primary objective is to develop a predictive model that can:

- Identify patients at high risk of medical complications.
- Prioritize and tailor prevention and intervention strategies based on individual patient characteristics.
- Contribute to improved patient outcomes and resource allocation within the healthcare system.

This project will play a crucial role in supporting healthcare providers and policymakers in their efforts to improve patient care and reduce healthcare costs.


# Dataset: Patient Treatment Classification (training_set.csv)

| HAEMATOCRIT | HAEMOGLOBINS | ERYTHROCYTE | LEUCOCYTE | THROMBOCYTE | MCH | MCHC | MCV | AGE | SEX | SOURCE |
|------------|--------------|------------|----------|------------|-----|------|-----|-----|-----|--------|
| 33.8       | 11.1         | 4.18       | 4.6      | 150        | 26.6| 32.8 | 80.9| 33  | F   | 1      |
| 44.6       | 14.0         | 6.86       | 6.3      | 232        | 20.4| 31.4 | 65.0| 36  | M   | 0      |
| 42.9       | 14.0         | 4.57       | 6.2      | 336        | 30.6| 32.6 | 93.9| 70  | F   | 0      |
| 41.9       | 14.4         | 4.67       | 3.5      | 276        | 30.8| 34.4 | 89.7| 18  | F   | 0      |
| 40.6       | 13.3         | 4.85       | 14.9     | 711        | 27.4| 32.8 | 83.7| 36  | M   | 0      |

## Team Information

**Team Name:** _HealthRisk Analysts_

**Team Members:**
1. Mitali Purohit
2. Tammy Xaypraseuth
3. Carlos Ramirez

**Supervised By:** Dr. Mohammad Pourhomayoun

**Teaching Assistants (TAs):**
- Ashkan Aledavoud
- Ly Jacky Nhiayi

## Overview

This GitHub repository hosts the code and documentation for the project "Identifying High-Risk Patients for Targeted Prevention and Intervention," a part of the Data Science 4661 course. The primary objective of this project is to develop a predictive model that identifies patients at high risk of medical complications by leveraging the knowledge and skills acquired during the course.

## Data

The predictive model will be trained on a comprehensive dataset of patient records, encompassing essential information such as demographic details, medical history, and laboratory test results.

## Methodology

Our approach follows a structured data science workflow:

- **Data Preparation**: This step involves loading the dataset, comprehending the features, handling missing values, encoding categorical variables, and scaling/normalizing numerical features.

- **Data Exploration**: We perform data visualization and analysis to gain valuable insights into data distribution, correlations, and patterns.

- **Model Building**: Multiple machine learning algorithms for classification tasks will be implemented and evaluated. The algorithms in consideration include K-Nearest Neighbors (KNN), Linear Regression, Logistic Regression, and Random Forest.

- **Model Selection**: We will select the most effective algorithm based on its performance when tested with separate validation data.

- **Model Deployment (optional)**: If deemed appropriate, the chosen model can be deployed in a real healthcare setting to predict medical complications in new patient data. This process, however, will strictly adhere to relevant data privacy and ethical guidelines.

## Machine Learning Algorithms

### Decision Tree Classifier
Decision Trees are used for feature importance analysis and understanding decision-making processes.

### Random Forest Classifier
Random Forest is an ensemble learning algorithm implemented for improved predictive performance.

### Logistic Regression
Logistic Regression is employed for binary classification tasks, providing interpretability of model coefficients.

### Linear Regression
Linear Regression is a regression algorithm used for predicting continuous numeric outcomes.

### K-Nearest Neighbors (KNN)
K-Nearest Neighbors is utilized for pattern recognition and classification.

### Support Vector Machine (SVM)
Support Vector Machine is employed for classification tasks, achieving an accuracy of 69.18%.

## Model Comparison

### ROC Curve

Receiver Operating Characteristic (ROC) curves are utilized to compare the performance of classification algorithms.

- [ROC Comparison Notebook](/patient_treatment_classification_ROC_comparison_v1.ipynb)

![ROC Curve](assets/roc.png)

## Cross-Validation Results

The machine learning model's performance was evaluated using cross-validation. The results are as follows:

- **Accuracy:** 0.75 (+/- 0.02)

This indicates the mean accuracy and the 95% confidence interval based on the cross-validation results.

[Cross-Validation Notebook](/patient_treatment_cross_validation_result.ipynb) 

### Results and Comparative Analysis
The accuracy scores obtained from each algorithm are compared, and the most effective algorithm is identified.

![Histogram of Accuracy Scores](assets/histogram.png)


## Documentation

This project is accompanied by comprehensive documentation that includes:

- **Code**: Detailed code snippets and scripts used throughout the project.
- **Steps Taken**: A clear and concise account of the actions taken at each stage.
- **Algorithm Rationale**: An explanation behind the choices of preprocessing steps and model evaluation criteria.
- **Model Evaluation**: Detailed insights into how well each model performs and the reasons for selecting the final model.

## Ethical and Legal Considerations

Ethical and legal aspects are pivotal when working with sensitive medical data. Our project is committed to:

- Protecting patient privacy by adhering to data protection and anonymization procedures.
- Ensuring the responsible use of the predictive model, considering the potential consequences on patient healthcare.
- Complying with all applicable laws and regulations related to medical data.

## Conclusion

The goal of the "Identifying High-Risk Patients for Targeted Prevention and Intervention" project is to develop a robust predictive model using a comprehensive dataset of patient records. The selected algorithm will be rigorously evaluated and, if applicable, deployed in a real healthcare setting. Throughout the project, we prioritize thorough documentation and unwavering adherence to ethical and legal considerations.


## Feature Importance Analysis

In-depth analysis of feature importance is conducted to interpret the decision-making processes of the models.

- [KNN Feature Importance Notebook](/output/knn_feature_importance.ipynb)

![KNN Feature Importance](assets/knn_feature_importance.png)

- [Random Forest Feature Importance Notebook](/output/random_forest_feature_importance.ipynb)

![Random Forest Feature Importance](assets/random_forest_feature_importance.png)

- [Decision Tree Feature Importance Notebook](/output/decision_tree_feature_importance.ipynb)

![Decision Tree Feature Importance](assets/decision_tree_feature_importance.png)

- [Logistic Regression Feature Importance Notebook](/output/logistic_regression_feature_importance.ipynb)

![Logistic Regression Feature Importance](assets/logistic_regression_feature_importance.png)

- [Linear Regression Feature Importance Notebook](/output/linear_regression_feature_importance.ipynb)

![Linear Regression Feature Importance](assets/linear_regression_feature_importance.png)

Feel free to explore our project's code, documentation, and insights. If you have any questions or feedback, please don't hesitate to get in touch.
