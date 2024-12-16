# Heart-Failure-Prediction-using-Neural-Networks

**Overview**
Heart failure is a critical medical condition that occurs when the heart cannot pump enough blood to meet the body’s needs. Early prediction of heart failure can significantly improve patient outcomes by enabling timely medical intervention. This project involves building a machine learning model to predict the likelihood of heart failure based on clinical data, such as patient demographics, laboratory results, and lifestyle factors.

**Objective**
The primary goal is to develop a predictive model that can accurately classify patients as being at risk of heart failure or not. This can assist healthcare professionals in making informed decisions regarding patient care.

**Dataset Descriptio**n
The dataset used for this project contains clinical records of patients, with the following key features:

Age: Age of the patient in years.

Anaemia: Whether the patient has a low red blood cell count (1 = Yes, 0 = No).

Creatinine Phosphokinase (CPK): Level of the CPK enzyme in the blood (mcg/L).

Diabetes: Whether the patient has diabetes (1 = Yes, 0 = No).

Ejection Fraction: Percentage of blood leaving the heart at each contraction (%).

High Blood Pressure: Presence of hypertension (1 = Yes, 0 = No).

Platelets: Platelet count in the blood (kiloplatelets/mL).

Serum Creatinine: Level of creatinine in the blood (mg/dL).

Serum Sodium: Level of sodium in the blood (mEq/L).

Sex: Gender of the patient (Male = 1, Female = 0).

Smoking: Whether the patient is a smoker (1 = Yes, 0 = No).

Time: Follow-up period (days).

Death Event: Target variable indicating if the patient died during follow-up (1 = Yes, 0 = No).

**Methodology**

**Data Preprocessing**:

Handle missing values and outliers.

Normalize or standardize numerical features.

Encode categorical variables if necessary.

**Exploratory Data Analysis (EDA)**:

Analyze the distribution of features.

Identify correlations between features and the target variable.

Visualize patterns using heatmaps, histograms, and box plots.

**Model Development**:

Split the data into training, validation, and testing sets.
Train various machine learning models (e.g., Logistic Regression, Random Forest, XGBoost) to identify the best performer.
Fine-tune hyperparameters using cross-validation techniques.

**Model Evaluation**:

Evaluate the model using metrics such as accuracy, precision, recall, F1 score, and ROC-AUC.

Analyze the confusion matrix to understand false positives and false negatives.

**Key Challenges**

Balancing the dataset if there is a class imbalance (e.g., significantly more non-fatal cases than fatal ones).

Avoiding overfitting, especially when dealing with small datasets.

Interpreting clinical data to ensure predictions align with medical knowledge.

**Outcome**
The final model predicts whether a patient is at risk of heart failure, with high accuracy and reliability. It can be used by healthcare providers as a decision-support tool to prioritize patients for further tests or interventions.

**Tools and Technologies**

Languages: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost, TensorFlow 

Environment: Google Colab

**Potential Applications**

Clinical Decision Support: Aid in identifying high-risk patients for further diagnostic testing.

Remote Health Monitoring: Integrate with wearable devices to predict heart failure risk in real-time.







