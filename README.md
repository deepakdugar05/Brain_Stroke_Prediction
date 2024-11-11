## Brain Stroke Prediction


# About Brain Stroke
Brain stroke is a medical emergency that occurs when the blood supply to part of the brain is interrupted or reduced. This sudden interruption can cause brain cells to die within minutes, leading to severe consequences. The impact of a stroke varies: some individuals recover completely, while others may have long-term disabilities affecting movement, speech, cognition, or other functions.

# Problem Statement
To develop a machine learning model capable of predicting the risk of an individual experiencing a stroke. Machine learning models can analyze factors like medical history, lifestyle, and health data to identify patterns indicating a higher risk of strokes. Early detection allows for timely intervention and preventive measures, potentially reducing the occurrence and severity of strokes.

# Data Description
The dataset used in this project includes the following attributes:

id: unique identifier
gender: "Male" or "Female"
age: age of the patient
hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
ever_married: "No" or "Yes"
work_type: "children", "Govt_job", "Private" or "Self-employed"
Residence_type: "Rural" or "Urban"
avg_glucose_level: average glucose level in blood
bmi: body mass index
smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"
stroke: 1 if the patient had a stroke or 0 if not

# Libraries Used
numpy
pandas
matplotlib
seaborn
scikit-learn
imbalanced-learn
Data Pre-Processing and EDA
Loaded the dataset and performed initial data analysis.
Checked for missing values and filled them appropriately.
Performed exploratory data analysis to understand the distribution and relationships between variables.
Model Training

# Utilized various machine learning algorithms to train the model, including:

Logistic Regression
Decision Tree Classifier
Random Forest Classifier
K-Nearest Neighbors
Support Vector Machine

# Conclusion
The project aims to build a predictive model for brain stroke risk, enabling healthcare providers to take proactive measures for at-risk individuals. The model's performance was evaluated using various metrics to ensure its effectiveness.

# License
This project is licensed under the MIT License. See the LICENSE file for details.

