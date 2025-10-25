# Heart Disease Prediction Project

This project aims to build a machine learning model to predict the presence of heart disease in patients based on a set of medical attributes mostly related to heart rate and blood exams.

## Goals

The primary goal of this project is to leverage machine learning to predict heart disease in individuals based on 11 key clinical features. Early detection of cardiovascular diseases (CVDs) is crucial for effective management and can significantly reduce mortality rates. This model is intended to serve as a tool to assist healthcare professionals in identifying high-risk patients.

## Data

The dataset used for this project contains medical information from patients and includes the following 11 features that are relevant for predicting heart disease.

**Context:**
Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worldwide. Four out of 5 CVD deaths are due to heart attacks and strokes, and one-third of these deaths occur prematurely in people under 70 years of age. Heart failure is a common event caused by CVDs and this dataset contains 11 features that can be used to predict a possible heart disease. People with cardiovascular disease or who are at high cardiovascular risk (due to the presence of one or more risk factors such as hypertension, diabetes, hyperlipidaemia or already established disease) need early detection and management wherein a machine learning model can be of great help.

**Attribute Information:**

*   **Age:** Age of the patient [years]
*   **Sex:** Sex of the patient [M: Male, F: Female]
*   **Chest Pain Type:** Type of chest pain [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
*   **Resting BP:** Resting blood pressure [mm Hg]
*   **Cholesterol:** Serum cholesterol [mm/dl]
*   **Fasting BS:** Fasting blood sugar [1: if Fasting BS > 120 mg/dl, 0: otherwise]
*   **Resting ECG:** Resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality, LVH: showing probable or definite left ventricular hypertrophy]
*   **Max HR:** Maximum heart rate achieved [Numeric value between 60 and 202]
*   **Exercise Angina:** Exercise-induced angina [Y: Yes, N: No]
*   **Oldpeak:** ST depression induced by exercise relative to rest
*   **ST_Slope:** The slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: down sloping]
*   **HeartDisease:** Output class [1: heart disease, 0: Normal]

## Analysis

The analytical process for this project will follow these key steps:

1.  **Exploratory Data Analysis (EDA):**
    *   Analyze the distribution of each feature.
    *   Visualize relationships between features and the target variable (HeartDisease).
    *   Identify and handle missing values or outliers.

2.  **Data Preprocessing:**
    *   Encode categorical variables (e.g., Sex, Chest Pain Type) into a numerical format.
    *   Scale numerical features to a common range to ensure that certain features do not dominate the model training process.

3.  **Model Training:**
    *   Split the dataset into training and testing sets.
    *   Train several classification models, such as:
        *   Logistic Regression
        *   Random Forest
        *   Gradient Boosting
        *   Support Vector Machines (SVM)

4.  **Model Evaluation:**
    *   Evaluate the performance of each model on the test set using metrics like:
        *   Accuracy
        *   Precision
        *   Recall
        *   F1-Score
        *   ROC Curve and AUC

5.  **Model Selection and Prediction:**
    *   Select the best-performing model based on the evaluation metrics.
    *   Use the final model to make predictions on new, unseen data of a different database.
