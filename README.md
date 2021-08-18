## Predicting Hospital Readmission for patients with diabetes
In 2011, more than 3.3 million patients were readmitted in the US within 30 days of being discharged. The readmission was associated with about $41 billion in hospital costs. The need for readmission indicates that inadequate care was provided to the patient at the time of first admission. The readmission rate has become an important metric measuring the overall quality of a hospital. To reduce healthcare cost and improve efficiency, there is a growing need to adopt predictive analytics to not only look at trends and facts, but to also predict valuable information to assist hospitals. 

The purpose of this project is to build a model that will be explicitly designed to predict if a diabetic patient is at risk of readmission to a hospital within 30 days of discharge. 

## About the dataset
The data used in this paper was derived from the UCI machine learning repository (https://archive.ics.uci.edu/ml/datasets/diabetes+130-us+hospitals+for+years+1999-2008). The dataset contained admission information for over 100,000 diabetic patients. The dataset covered information from 130 hospitals and integrated network delivery systems showing ten years (between 1999-2008) of clinical care. The data contains attributes such as patient number, race, gender, age, admission type, time in hospital, medical specialty of admitting physician, number of lab test performed, HbA1c test result, diagnosis, number of medication, diabetic medications, number of outpatient, inpatient, and emergency visits in the year before the hospitalization, etc.

## Conclusion
Through this project, we created a model to predict the probability that a patient with diabetes would be readmitted to the hospital within 30 days. Our best model had an AUC of of 0.67. Using this model, we are able to catch 58% of the readmissions from our model that performs approximately 1.5 times better than randomly selecting patients.
