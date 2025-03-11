# heart-failure-prediction

This project aims to predict the likelihood of heart failure based on various medical attributes, using machine learning models.

## Dataset Columns:
- **Age**: Age of the patient.
- **Sex**: Gender of the patient (male or female).
- **ChestPainType**: Type of chest pain experienced by the patient.
- **RestingBP**: Resting blood pressure (mm Hg).
- **Cholesterol**: Serum cholesterol level (mg/dl).
- **FastingBS**: Fasting blood sugar (1 if greater than 120 mg/dl, 0 otherwise).
- **RestingECG**: Resting electrocardiographic results.
- **MaxHR**: Maximum heart rate achieved.
- **ExerciseAngina**: Whether the patient experiences angina during exercise (1 if yes, 0 if no).
- **Oldpeak**: Depression induced by exercise relative to rest.
- **ST_Slope**: Slope of the peak exercise ST segment.
- **HeartDisease**: Target variable indicating if the patient has heart disease (1 = yes, 0 = no).

## Objective:
Predict the presence of **HeartDisease** (1: Yes, 0: No) using the listed medical attributes.

## Steps:
1. **Exploratory Data Analysis (EDA)**: Data cleaning, visualisation, and understanding relationships.
2. **Model Building**: Various classification models (e.g., Logistic Regression, Random Forest, XGBoost) to predict heart failure.
3. **Evaluation**: Model performance evaluation using metrics like accuracy, confusion matrix, and ROC-AUC.

## Packages:
Install the required dependencies using the requirements.txt file
 ```bash
   pip install -r requirements.txt
