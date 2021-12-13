
## Background & Motivation

The cost of hospital readmission accounts for a large portion of hospital inpatient services spending. 
Diabetes is not only one of the top ten leading causes of death in the world, but also the most expensive chronic disease in the United State. 
Hospitalized patients with diabetes are at higher risk of readmission than those without diabetes. 
Therefore, reducing readmission rates for diabetic patients has a great potential to reduce medical cost significantly. 

## Objective

The objective of this study is to predict the likelihood of a diabetic patient being readmitted.


## Dataset

The original dataset was obtained from the Center for Machine Learning and Intelligent Systems at University of California, Irvine. It was collected from 130 hospitals in the U.S. during a period of 10 years (1999 to 2008). It contains 101,766 observations and 50 features. After cleaning the data, it was left with 27 features. These are:
* Race (Caucasian, African American, Asian, Other)
* Gender (Male, Female)
* Age (0-40, 40-50, 50-60, 60-70, 70-80, 80-100)
* Admission Type (Emergency, Elective, Other, Newborn)
* Discharge Disposition (Home, Other)
* Admission Source (Emergency Room, Physician Referral, Other)
* Time in hospital: Number of days between admission and discharge
* Number of lab procedures: Numeric number of lab tests performed during the encounter
* Number of procedures: Numeric number of procedures (other than lab tests) performed during the encounter
* Number of medications: Number of distinct generic names administered during the encounter
* Number of outpatient visits: Number of outpatient visits of the patient in the year preceding the encounter
* Number of emergency visits: Number of emergency visits of the patient in the year preceding the encounter
* Number of inpatient visits: Number of inpatient visits of the patient in the year preceding the encounter
* Number of diagnoses: Number of diagnoses entered to the system 0%
* Glucose serum test result (>200, >300, normal, and none if not measured): Indicates the range of the glucose serum test result.
* HbA1c test result (>8 if the result was greater than 8%, >7 if the result was greater than 7% but less than 8%, normal if the result was less than 7%, and none if not measured): Indicates the range of the result or if the test was not taken.
* 7 features for medications for the generic names: metformin, glimepiride, glipizide, glyburide, pioglitazone, rosiglitazone, insulin (Up if the dosage was increased during the encounter, down if the dosage was decreased, steady if the dosage did not change, and no if the drug was not prescribed): Indicates whether the drug was prescribed or there was a change in the dosage. 
* Change of medications (change and no change): Indicates if there was a change in diabetic medications (either dosage or generic name).
* Diabetes medications (yes and no): Indicates if there was any diabetic medication prescribed. 
* Readmitted Days to inpatient readmission (0 if the patient was readmitted in more than 30 days or there is no record of readmission and 1 if the patient was readmitted in less than 30 days
