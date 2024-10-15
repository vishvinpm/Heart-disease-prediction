# Heart-disease-prediction
This repository contains a case study on Heart Disease Prediction using the Framingham Heart Study dataset and various machine learning algorithms. The goal is to predict whether a patient will develop heart disease based on clinical and lifestyle features.
## Problem statement
Heart disease remains one of the leading causes of death worldwide, and early prediction of heart disease risk can lead to preventive measures and improved patient outcomes. This case study leverages the Framingham Heart Study dataset, which contains long-term cardiovascular data, to build predictive models for heart disease.

We explore various machine learning models, including Logistic Regression, to predict the likelihood of a patient developing heart disease based on demographic, medical, and lifestyle factors.

## About the dataset
The dataset used in this project is the Framingham Heart Study dataset, a comprehensive dataset that includes data on cardiovascular risk factors over several decades. This dataset is publicly available and widely used in heart disease prediction research.

- Source: The Framingham Heart Study dataset is available from the [Framingham Heart Study](https://www.framinghamheartstudy.org/) website, but you can find versions on platforms like [Kaggle](https://www.kaggle.com/datasets/aasheesh200/framingham-heart-study-dataset).

Number of instances: ~5,000

Number of features: 15 (including the target variable)

- Target variable : TenYearCHD (1 if the patient is diagnosed with coronary heart disease within ten years, 0 otherwise).

### Features
| Feature | Description |
|:--------|:------------|
|male |Indicates gender (1 = male, 0 = female).|
|age|Age of the person.|
|education | Level of education (categorical variable, coded as numbers).|
|currentSmoker| Indicates if the person is a current smoker (1 = yes, 0 = no).|
|cigsPerDay| Average number of cigarettes smoked per day (for current smokers).|
|BPMeds|  Use of blood pressure medication (1 = yes, 0 = no).|
|prevalentStroke|History of a stroke (1 = yes, 0 = no).|
|prevalentHyp|Prevalent hypertension (1 = yes, 0 = no).|
|diabetes|Indicates if the person has diabetes (1 = yes, 0 = no).|
|totChol|Total cholesterol level.|
|sysBP|Systolic blood pressure.|
|diaBP|Diastolic blood pressure.|
|BMI|Body Mass Index.|
|heartRate|Heart rate (beats per minute).|
|glucose|Glucose level.|
|TenYearCHD|10-year risk of coronary heart disease (1 = diagnosed within 10 years, 0 = not diagnosed).|
