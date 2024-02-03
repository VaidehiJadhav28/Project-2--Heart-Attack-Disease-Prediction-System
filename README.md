Heart Attack Risk Prediction Project 

Introduction:
The Heart Attack Risk Prediction project aims to leverage the Heart Attack Risk Prediction Dataset to develop models capable of predicting the likelihood of a heart attack based on various health attributes. The dataset encompasses diverse features such as age, cholesterol levels, blood pressure, smoking habits, exercise patterns, and dietary preferences. The goal is to contribute to proactive strategies for heart disease prevention and management.

The dataset consisted of:-

Dataset Glossary (Column-wise)
Patient ID - Unique identifier for each patient
Age - Age of the patient
Sex - Gender of the patient (Male/Female)
Cholesterol - Cholesterol levels of the patient
Blood Pressure - Blood pressure of the patient (systolic/diastolic)
Heart Rate - Heart rate of the patient.
Diabetes - Whether the patient has diabetes (Yes/No)
Family History - Family history of heart-related problems (1: Yes, 0: No)
Smoking - Smoking status of the patient (1: Smoker, 0: Non-smoker)
Obesity - Obesity status of the patient (1: Obese, 0: Not obese)
Alcohol Consumption - Level of alcohol consumption by the patient (None/Light/Moderate/Heavy)
Exercise Hours Per Week - Number of exercise hours per week.
Diet - Dietary habits of the patient (Healthy/Average/Unhealthy)
Previous Heart Problems - Previous heart problems of the patient (1: Yes, 0: No)
Medication Use - Medication usage by the patient (1: Yes, 0: No)
Stress Level - Stress level reported by the patient (1-10)
Sedentary Hours Per Day - Hours of sedentary activity per day
Income - Income level of the patient.
BMI - Body Mass Index (BMI) of the patient
Triglycerides - Triglyceride levels of the patient
Physical Activity Days Per Week - Days of physical activity per week
Sleep Hours Per Day - Hours of sleep per day
Country - Country of the patient
Continent - Continent where the patient resides
Hemisphere - Hemisphere where the patient resides
Heart Attack Risk - Presence of heart attack risk (1: Yes, 0: No)

The shape of the dataset is- (Rows, columns): (8763, 26)

Project Overview:
1. Data Collection: Acquired a comprehensive dataset containing information on individuals' health attributes, serving as the foundation for model development.

2. Data Preprocessing: Conducted thorough preprocessing tasks, including handling missing values, encoding categorical variables, and scaling numerical features to ensure data quality and compatibility with machine learning models.

3. Feature Selection: Employed feature selection techniques to identify the most relevant attributes contributing to the prediction of heart attacks, enhancing model efficiency.

4. Model Development: Implemented Support Vector Machine (SVM), Logistic Regression, and Random Forest models to predict the likelihood of heart attacks based on the selected features.

5. Cross-Validation: Utilized cross-validation techniques to assess the models' performance, ensuring robustness and generalizability.

6. Hyperparameter Tuning: Fine-tuned model hyperparameters to optimize predictive accuracy and achieve better performance.

7. Validation and Testing: Evaluated model performance on validation and testing datasets to measure accuracy and understand each model's predictive capabilities.

Model Performance:
1. Support Vector Machine (SVM):
   - Accuracy: 47.35%
   - Precision: 0.46
   - Recall: 0.46
   - F1-score: 0.49

2. Logistic Regression:
   - Accuracy: 65.15%
   - Precision: 0.33
   - Recall: 0.50
   - F1-score: 0.39

3. Random Forest:
   - Accuracy: 63.89%
   - Precision: 0.47
   - Recall: 0.50
   - F1-score: 0.41

Conclusion:
- The Logistic Regression model demonstrated the highest accuracy among the three models, achieving 65.15% accuracy.
- All models showed challenges in predicting the positive class (presence of a heart attack), indicating potential areas for improvement or further investigation.
- The project contributes valuable insights into the complexities of heart health prediction and provides a foundation for future enhancements in model performance and healthcare strategies.

- This project is an ongoing effort, and continuous refinement and updates are encouraged for improved predictive capabilities and real-world applicability.
