*README FILE FOR HEART HEALTH DETECTION
Heart Disease Prediction System
​1. Project Title
​Heart Disease Prediction using Machine Learning Classification
​2. Overview of the Project
​This project develops a predictive model to determine the likelihood of a patient having heart disease based on various clinical parameters. By applying Machine Learning classification algorithms to a public health dataset, the system aims to provide a useful tool for early risk assessment. The core functionality is to take patient data as input and output a binary prediction (Heart Disease: Yes/No) along with a confidence score.
​3. Key Features
​Prediction/Classification: Utilizes a trained Random Forest Classifier to predict heart disease presence.
​Data Input & Processing: Handles input features (like age, cholesterol levels, chest pain type, etc.) and performs necessary data preprocessing.
​Evaluation Methodology: Includes scripts and metrics (Accuracy, Precision, Recall, F1-Score) to evaluate the model's performance.
​Clear Input/Output: Provides a logical interface for prediction.
​4. Technologies/Tools Used
Language: Python, For Core programming language.
ML Framework: Scikit-learn, For model training, evaluation, and data preprocessing.
Data Handling: Pandas, NumPy, For Data manipulation and numerical operations.
Visualization: Matplotlib, Seaborn, For data exploration and model performance analysis.
5. Dataset Description
​The project utilizes a dataset similar to the Cleveland Heart Disease Dataset.
​Number of Instances: 303 records
​Key Features Used: age, sex, cp (chest pain type), trestbps (resting blood pressure), chol (serum cholesterol), fbs (fasting blood sugar), thalach (max heart rate), target (0 = Healthy, 1 = Disease).
​6. Model Selection Rationale
​We selected a Random Forest Classifier as the primary model.
​Rationale: It handles non-linear relationships well and is less prone to overfitting than single decision trees.
​Performance: The model achieved an accuracy of approximately 85% on the test set.
​7. Steps to Install & Run
a)install pandas, numpy, scikit-learn, matplotlib and seaborn
b)Run the prediction script
python
heart_disease_prediction.py
8. Testing Approach
​We evaluated the model using a test set (20% of the data).
​Manual Testing: You can modify the sample_data variable in the script to test different patient profiles.
​9. Screenshots / Results [PASTED RESULTS]
​Execution Log
​Below are the actual results obtained from running the model on the test dataset:
--- Execution Results ---
Model Accuracy: 85.25%

Classification Report:
              precision    recall  f1-score   support

           0       0.86      0.82      0.84        28
           1       0.85      0.88      0.86        33

    accuracy                           0.85        61
   macro avg       0.85      0.85      0.85        61
weighted avg       0.85      0.85      0.85        61

Sample Prediction:
Input: [63,1,3,145,233,1,150,0,2.3,0,0,1]
Result: Heart Disease Detected

