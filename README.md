
---

#  Diabetes Risk Prediction App

A machine learning application for predicting diabetes risk based on various health metrics using an XGBoost Regressor model.

## Overview

This project provides an interactive interface for users to input their health information and receive a prediction about their diabetes risk status. The model was trained on a comprehensive dataset of health metrics and can classify patients into three categories: No Diabetes, Prediabetes, or Diabetes.

##  Features

- Easy-to-use interface for inputting health metrics  
- Instant prediction of diabetes risk status  
- Visual representation of risk level  
- Identification of key risk factors  
- Personalized recommendations based on prediction results  
- Designed for both technical and non-technical users  

##  Technical Details

- **Model**: XGBoost Regressor  
- **Data Processing**: SimpleImputer for handling missing values  
- **Visualization**: Matplotlib and Seaborn  
- **Data Handling**: Pandas and NumPy  



## Dataset

The model was trained on a diabetes dataset containing the following features:

- Demographic information (Age, Sex)  
- Body measurements (BMI, Waist Circumference)  
- Blood tests (Fasting Blood Glucose, HbA1c)  
- Blood pressure (Systolic, Diastolic)  
- Cholesterol levels (Total, HDL, LDL)  
- Other tests (GGT, Serum Urate)  
- Lifestyle factors (Physical Activity Level, Dietary Intake, Alcohol Consumption, Smoking Status)  
- Medical history (Family History of Diabetes, Previous Gestational Diabetes)  

## How It Works

1. The user provides health information via a data input method (UI, script, or form).  
2. The data is processed using the same imputer used during model training.  
3. The trained XGBoost model generates a prediction.  
4. Results are displayed, saved, or returned based on implementation.  
5. Key risk factors can be extracted from the input and output.  
6. Personalized recommendations can be attached to different prediction thresholds.

##  Accuracy

This project achieved an accuracy of 98.5%, with an R² score of `0.9854798308252408`.

## Files Description

- `diabetic_prediction.pkl`: Serialized XGBoost model  
- `imputer.pkl`: Serialized SimpleImputer for handling missing values  
- `requirements.txt`: List of Python dependencies  
- `README.md`: Project documentation  

##  Future Improvements

- Add more visualization options for exploring risk factors  
- Include detailed explanations of individual health metrics and their impacts  

##  Disclaimer

This application is for informational purposes only and should not be considered as medical advice. Always consult with a healthcare professional for proper diagnosis and treatment.

## 🧑🏻‍🎓 Author

[Yuva Shankar Narayana](https://www.linkedin.com/in/yuva-shankar-narayana/)

---

Let me know if you'd like this converted into a real `README.md` file or want to keep both Streamlit and non-Streamlit versions!
