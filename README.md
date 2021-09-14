![patient](https://images.unsplash.com/photo-1576766125535-b04e15fd0273?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80)

# Survival-of-a-Patient

 ## Business Problem  
 A hospital has been trying to improve its care conditions by analyzing the historic survival of its patients. They tried looking at their data but could not identify the main factors leading to high survivals.
 
 ## The dataset

The dataset contains the patient records collected from a hospital. 

The "Survived_1_year" column is a target variable which has binary entries (0 or 1).

•	Survived_1_year == 0, implies that the patient did not survive after 1 year of treatment

•	Survived_1_year == 1, implies that the patient survived after 1 year of treatment

•	D_Patient_Care_Situation: Care situation of a patient during treatment

•	Diagnosed_Condition: The diagnosed condition of the patient

•	ID_Patient: Patient identifier number

•	Treatment_with_drugs: Class of drugs used during treatment

•	Survived_1_year: If the patient survived after one year (0 means did not survive; 1 means survived)

•	Patient_Age: Age of the patient

•	Patient_Body_Mass_Index: A calculated value based on the patient’s weight, height, etc.

•	Patient_Smoker: If the patient was a smoker or not

•	Patient_Rural_Urban: If the patient stayed in Rural or Urban part of the country

•	Previous_Condition: Condition of the patient before the start of the treatment ( This variable is splitted into 8 columns - A, B, C, D, E, F, Z and Number_of_prev_cond. A, B, C, D, E, F and Z are the previous conditions of the patient.

 
 ## Objective
 
To develop a model that will predict the chances of survival of a patient after 1 year of treatment.
 
## Requirements 
Libraries used - To succesfully run this Jupyter notebook the following libraries need to be installed.

    - Python 3     - Pandas     - Scikit-Learn     - Seaborn     - Matplotlib     - Numpy  
    
## Data Preprocessing
Preprocessing work done on the data included:

1. Outlier removal

2. Label and one hot encoding for categorical data

3. Handling of missing data by median imputation

4. Replacing missing values  with a hard coded values like zero (eg 1 for yes, 0 for none)



## Models 
1.Gradient Boosting Classifier

2.Ada Boost Classifier

3.Random Forest Classifier

4.Naive Bayes

5.K Nearest Neighbors

6.Decision Tree Classifier

7.Logistic Regression

## Results
Performance Evaluation Metric used:

1.F1 score

2.AUC score

3.Training and test accuracy

4.Confusion matrix

