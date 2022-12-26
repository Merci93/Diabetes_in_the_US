# Data Set Information
The dataset represents 10 years (1999-2008) of clinical care at 130 US hospitals and 
integrated delivery networks. It includes over 50 features representing patient and 
hospital outcomes. Information was extracted from the database for encounters that 
satisfied the following criteria:

1. It is an inpatient encounter (a hospital admission).
2. It is a diabetic encounter, that is, one during which any kind of diabetes was entered 
to the system as a diagnosis.
3. The length of stay was at least 1 day and at most 14 days.
4. Laboratory tests were performed during the encounter.
5. Medications were administered during the encounter.

The data contains such attributes as patient number, race, gender, age, admission type, time 
in hospital, medical specialty of admitting physician, number of lab test performed, HbA1c 
test result, diagnosis, number of medication, diabetic medications, number of outpatient, 
inpatient, and emergency visits in the year before the hospitalization, etc.

24 features for medications For the generic names: metformin, repaglinide, nateglinide, 
chlorpropamide, glimepiride, acetohexamide, glipizide, glyburide, tolbutamide, pioglitazone, 
rosiglitazone, acarbose, miglitol, troglitazone, tolazamide, examide, sitagliptin, insulin, 
glyburide-metformin, glipizide-metformin, glimepiride-pioglitazone, metformin-rosiglitazone, 
and metformin-pioglitazone, the feature indicates whether the drug was prescribed or there 
was a change in the dosage. Values: “up” if the dosage was increased during the encounter, 
“down” if the dosage was decreased, “steady” if the dosage did not change, and “no” if the 
drug was not prescribed.

The dataset represents a record of 10 years of diabetes patients treatment and hospital visitation
in the United States from 1999 to 2008. The dataset contains clinical care at 130 US hospitals and
integrated delivery networks. It includes over 50 features representing patient and hospital
outcomes. Included in the features are race, gender, age, diabetes medication and more.
Analysis and visualizations will be performed using this data to derive insights on the
relationships between diabetes patients and age, weight, race, gender, insulin level and effects
of medications when recommended. The dataset contains 101,766 rows and 51 columns.

# Conclusion
Though the datatset had lots of tidyness and cleanliness issues which were resolved, the following
deductions were made:

1. During the period under consideration, the female gender had more occurrence of diabetes.
2. The age range for diabetic pateints is between 50 years to 89 years.
3. Caucassian race had the most occurrence of diabetes, though a good number were also 
African_American.
4. Probability of diabetic condition is higly related to insulin level and A1C_result test.

#### PS: These conclusions and more are not imply any statistical meaning as this analysis was
carried out for study purposes.