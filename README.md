# Early Identification of Stroke : Project Overview🎯
## Problem statement
Stroke is sometimes termed as brain attack or a cardiovascular accident (CVA). It is much like a heart attack, only it occurs in the brain.<br>

It occurs when the supply of blood to the brain is reduced or blocked completely, which prevents brain tissue from getting oxygen and nutrients.<br>

According to the World Health Organization (WHO) stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths.<br>
Early identification of stroke can help doctors to give necessary medication to the patient.


## Machine Learning problem
Predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status.<br>
<b>Type</b> : Supervised Learning<br>
<b>Task</b> : Binary classification<br>
<b>Performance metric</b> : F1 score (since imbalanced classes)<br>

## About Dataset
Source : https://www.kaggle.com/fedesoriano/stroke-prediction-dataset

### Attribute Information
<b>id</b>: unique identifier<br>
<b>gender</b>: Male, Female or Other<br>
<b>age</b>: age of the patient<br>
<b>hypertension</b>: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension<br>
<b>heart_disease</b>: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease<br>
<b>ever_married</b>: No or Yes<br>
<b>work_type</b>: children, Govt_jov, Never_worked, Private or Self-employed<br>
<b>Residence_type</b>: Rural or Urban<br>
<b>avg_glucose_level</b>: average glucose level in blood<br>
<b>bmi</b>: body mass index<br>
<b>smoking_status</b>: formerly smoked, never smoked, smokes or Unknown<br>
<b>stroke</b>: 1 if the patient had a stroke or 0 if not (target)<br>


# Tools and Technologies used🛠
- Windows 10 OS 
- Python 3.7
- Pandas
- Numpy
- Malplotlib 
- Seaborn 
- Sklearn
- Flask
- HTML
- CSS
- BootStrap 
- Deployed on Heroku cloud

**A web application to predict the chances of getting stroke by a patient based on other health factors like hypertension, Smoking habit, etc.**
- Live app :- https://brain-stroke-aditi-101803650.herokuapp.com/
- The model was trained and validated on 5100+ patient health records. 
- Achieved True Positive rate of 0.77 and F1 score of 0.24
