# Foundation of Data Science Project Report: Data Analysis for De-identified NY Inpatient Discharge (SPARCS)

### Introduction:
Under the background of our age, data has started to play a vital role across so many fields that elevating our efficiency
and creating precious value for the development of our society. As the advancement of our technology and capacious access 
to data, we are able to apply all kinds of techniques to refine valuable and precious information and to help us to make 
better decisions and analysis. For this data science project, we applied the techniques that we learned in the Data Science 
course to analyze the diagnostic information of patients in hospitals in Mount Sinai hospitals in 2015. 

### 1.1 Data Information:
For this project, we have chosen to explore the dataset of 2015 De-identified NY Inpatient Discharge, which was collected from the Statewide Planning and Research Cooperative System (SPARCS). The data are saved in a single CSV file with 2.35 million rows, and 37 columns. Each row represents a patient who was discharged from the hospital. Each column represents a feature relative to the patient, such as the patient’s age range, race, length of stay, and type of admission. To protect the privacy of patients, their names were removed.

### 1.2 Data Validation:
CSV file:
2.35 million rows, and 37 columns
Each row: → one Discharged patients 
Each column: → Features of patients
Such as:  length of stay, age group, race, diagnosis results, and different hospitals

Data cleaning:
Reduce the scope of our investigation 
Hospitals of NY→ Mount sinai 

Patients from New York city: 47% 
→ Mount Sinai Hospital (2.4%=55996 patients)

Deleting unnecessary features of patients
Repeat or irrelevant data
Change data types
Delete extra symbols

### 1.3 Problems For Analysis
There are four questions we wish to explore with this data analysis project:
- How is the diagnosis description affecting the total charges of staying in the hospital and which diagnosis has the most total charges in the Mount Sinai Hospital?
- What is the relationship between the length of staying at the hospital and the total charges generated,  and can we predict the total charges base on the length of staying?
- Is there a relationship between the severity code of illness and length of stay & age, and what information can we extract from this relationship?
- What is the difference between the charges generated using Medicaid and Medicare with respect to certain diagnosis descriptions?

