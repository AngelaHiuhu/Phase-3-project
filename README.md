# Phase-3-project
## PROJECT DELIVERABLES
1. BUSINESS PROBLEM
2. DATA UNDERSTANDING
3. DATA PREPARATION
4. MODELLING
5. MODEL QUALITY EVALUATION
6. CONCLUSIONS AND RECOMMENDATIONS

## BUSINESS PROBLEM

There has been an increase in the number of reported cases of people being unreasonably arrested after being stopped by the police and this has caused an outrage among the citizens. Therefore, my client who is the head of the National Transport and Safety Authority (NTSA) is interested in finding out whether arrests made after a Terry stop were reasonable or unreasonable based on factors outlined in the dataset

### BUSINESS OBJECTIVES

1. Determining whether the gender or the race of a subject influenced his or her arrest.
2. Determining whether the type of race or gender of an officer influences the number of arrests he or she makes.
3. Determining whether certain precincts report the most arrests.
4. Determine whether there is a direct correlation between the frisks and the arrests.
5. Determine whether the final call type influences an arrest or not.

### COLUMN DESCRIPTION
1. 'Subject Age Group' - Subject Age Group (10 year increments) as reported by the officer.
2. 'Subject ID' - a unique character to character match of first name and last name. "Null" values indicate an "anonymous" or "unidentified" subject. 
3. 'GO / SC Num' - General Offense or Street Check number.
4. 'Terry Stop ID' - Key identifying unique Terry Stop reports
5. 'Stop Resolution' - Resolution of the stop as reported by the officer.
6. 'Weapon Type' - Type of weapon, if any, identified during a search or frisk of the subject. Indicates "None" if no weapons was found.
7. 'Officer ID' - Key identifying unique officers in the dataset.
8. 'Officer YOB' - 	Year of birth, as reported by the officer.
9. 'Officer Gender' - Gender of the officer.
10. 'Officer Race' - Race of the office.
11. 'Subject Perceived Race' - Perceived race of the subject.
12. 'Subject Perceived Gender', - Perceived gender of the subject.
13. 'Reported Date' - Date the report was filed in the Records Management System.
14. 'Reported Time' - Time the stop was reported in the Records Management System.
15. 'Initial Call Type' - Initial classification of the call as assigned by 911.
16. 'Final Call Type' - Final classification of the call as assigned by the primary officer closing the event.
17. 'Call Type' - How the call was received by the communication center.
18. 'Officer Squad' - Functional squad assignment (not budget) of the officer as reported by the Data Analytics Platform.
19. 'Arrest Flag' - Indicator of whether a "physical arrest" was made, of the subject, during the Terry Stop. Does not necessarily reflect a report of an arrest in the Records Management System
20. 'Frisk Flag' - Indicator of whether a "frisk" was conducted, by the officer, of the subject, during the Terry Stop.
21. 'Precinct' - Precinct of the address associated with the underlying Computer Aided Dispatch (CAD) event. Not necessarily where the Terry Stop occurred.
22. 'Sector' - Sector of the address associated with the underlying Computer Aided Dispatch (CAD) event. Not necessarily where the Terry Stop occurred.
23. 'Beat' - Beat of the address associated with the underlying Computer Aided Dispatch (CAD) event. Not necessarily where the Terry Stop occurred.

## CONCLUSION & RECOMMENDATION
*High Accuracy: The model performs well, showing accurate predictions with high AUC values for both training and testing.​
*Good Generalization: The small difference between the AUCs for training and testing indicates that the model minimizes overfitting and generalizes effectively to new data.
*Consistent Performance: Reliable and consistent performance is essential for real-world applications, as indicated by the close proximity of AUC values between training and testing.
In brief:​
*Outstanding Accuracy: The model's remarkable AUC scores and high accuracy demonstrate its potent prediction powers.​
*Minimal Overfitting: Good generalization to unknown data is indicated by the marginally higher test AUC when compared to the training AUC.​
*Reliable Predictions: The model's predictions are deemed adequate for real-world applications due to the consistently high AUC values throughout both training and testing sets.
