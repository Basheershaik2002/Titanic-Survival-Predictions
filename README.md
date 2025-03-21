# Titanic-Survival-Prediction

### Task Overview:

This task uses machine learning to predict whether a passenger survived the Titanic disaster based on key features such as passenger class, age, gender, fare, and number of family members aboard. The dataset is preprocessed, and a Random Forest model is trained to classify passengers as "Survived" or "Not Survived".

### Dataset Information:

The dataset consists of 891 records with the following features:

Pclass – Passenger class (1st, 2nd, 3rd)

Sex – Gender (Male/Female)

Age – Age of the passenger

SibSp – Number of siblings/spouses aboard

Parch – Number of parents/children aboard

Fare – Ticket fare paid

Embarked – Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

Survived (Target) – 1 (Survived), 0 (Not Survived)

 ### Project Workflow:
 
1️ Data Preprocessing

✔ Handling missing values in Age and Embarked

✔ Encoding categorical features (Sex, Embarked)

✔ Dropping unnecessary columns (Name, Ticket, Cabin)


### How to Run the Task:

1. Clone the Repository:

git clone <repository-url>
cd titanic-survival-prediction

 2. Install Dependencies

pip install -r requirements.txt

### Expected Outcome:

Accurate Survival Prediction using a trained ML model

Interactive Web App with an easy-to-use interface

Insights into Passenger Survival Trends

## Conclusion:

This project effectively demonstrates how machine learning can analyze historical data to uncover patterns and make predictions. By leveraging data preprocessing, feature selection, and model evaluation, we gained valuable insights into survival factors during the Titanic disaster. The results highlight the significant role of class, gender, and age in determining survival probabilities. The model's findings align with historical records, showing how data-driven approaches can provide meaningful interpretations of real-world events.
