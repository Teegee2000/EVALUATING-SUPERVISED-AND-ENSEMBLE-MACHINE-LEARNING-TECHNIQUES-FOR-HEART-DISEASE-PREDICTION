This project uses multiple machine learning models to predict heart disease based on a dataset containing various health indicators. It explores different classification algorithms, including KNN, SVM, Logistic Regression, Naive Bayes, and ensemble techniques such as Gradient Boosting, Bagging, Stacking, and Voting Classifiers.


Overview

The goal of this project is to classify whether a patient is likely to have heart disease based on several features such as age, gender, cholesterol levels, and more. The project evaluates multiple machine learning algorithms to find the best-performing model.

The dataset is sourced from Kaggle.


Dataset 

Age: Age of the patient.

Sex: Gender of the patient (0 = female, 1 = male).

ChestPainType: Type of chest pain (e.g., typical angina, atypical angina).

RestingBP: Resting blood pressure (in mm Hg).

Cholesterol: Serum cholesterol level (mg/dl).

FastingBS: Fasting blood sugar (> 120 mg/dl, 1 = true, 0 = false).

RestingECG: Resting electrocardiographic results.

MaxHR: Maximum heart rate achieved.

ExerciseAngina: Exercise-induced angina (1 = yes, 0 = no).

Oldpeak: ST depression induced by exercise relative to rest.

Slope: The slope of the peak exercise ST segment.

Ca: Number of major vessels colored by fluoroscopy.

Thal: Thalassemia (normal, fixed defect, reversible defect).

Target: The target variable (1 = heart disease, 0 = no heart disease).

Usage

Data Preprocessing: The dataset is split into training and testing sets using train_test_split.

Model Training: Several models are trained and evaluated:

K-Nearest Neighbors (KNN)

Support Vector Machine (SVM)

Logistic Regression

Naive Bayes

Gradient Boosting

Bagging Classifier

Stacking Classifier

Voting Classifier

Evaluation

The models are evaluated using:

Confusion Matrix

ROC Curve


Model	Accuracy
KNN	73%

SVM	68%

Logistic Regression	79%

Naive Bayes	80%

Gradient Boosting	93%

Bagging Classifier	99%

Stacking Classifier	99%

Voting Classifier	92%

which makes ensemble model better to predict heart disease prediction because it's combination of 2 supervised machine learning models, which make it more efficient and highly recommendation for heart prediction 


include it that the data was gotten from kaggle 
