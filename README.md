# Heart-RIsk-Prediction
A ML model to predict heart risks using various demographics like Cholestrol, age, ECG etc.

# About Dataset
Context
This data set dates from 1988 and consists of four databases: Cleveland, Hungary, Switzerland, and Long Beach V. It contains 76 attributes, including the predicted attribute, but all published experiments refer to using a subset of 14 of them. The "target" field refers to the presence of heart disease in the patient. It is integer valued 0 = no disease and 1 = disease.

# Attribute Information:

- age
- sex
- chest pain type (4 values)
- resting blood pressure
- serum cholestoral in mg/dl
- fasting blood sugar > 120 mg/dl
- resting electrocardiographic results (values 0,1,2)
- maximum heart rate achieved
- exercise induced angina
- oldpeak = ST depression induced by exercise relative to rest
- the slope of the peak exercise ST segment
- number of major vessels (0-3) colored by flourosopy
- thal: 0 = normal; 1 = fixed defect; 2 = reversable defect

#  Exploratory Data Analysis
There are 3 key risk factors for heart disease. High blood pressure, high blood cholesterol, smoking.
Anyway, the scatter plot show 2 key risk factors focus over 30 years old people:

- Heart Disease - Cholesterol & Age
- Heart Disease - Resting Blood Pressure & Age
- Performed exploratory data analysis, Implemented data oversampling(SMOTE) & undersampling
- What problems does high blood pressure cause?
High blood pressure can damage your health in many ways. It can seriously hurt important organs like your heart, brain, kidneys, and eyes.
The good news is that, in most cases, you can manage your blood pressure to lower your risk for serious health problems.
High blood pressure can damage your arteries by making them less elastic, which decreases the flow of blood and oxygen to your heart and leads to heart disease.

• Developed a Streamlit-based user interface enabling users to input patient details and determine their heart condition

# ML Model
• Utilized diverse models(Random Forest,Voting Classifier) and achieved ∼91% accuracy using soft Voting Classifier




