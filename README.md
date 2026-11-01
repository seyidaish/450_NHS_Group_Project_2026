# 450 NHS Group Project 2026

### Project Outline
**Predicting a Patient’s Length of Stay**

**Description:**
Differing demands for bed capacity create difficulty with allocating acute hospital beds. The managers often need to rely on their own experience, initiative, data and forecasts during this process. Recently, AI tools and other statistical methods have helped with decision making process for bed managers. Methods also assist with predicting an individual’s length of stay - length between admittance and discharge from hospital. Predictions can be completed with the consideration of a range of patient information → demographics, diagnoses and comorbidities.


**Task:**

1. Explore the dataset and summarise it.
2. Build and evaluate a model which predicts patient length of stay in days or hours.
3. Suggest additional data which could be used to improve your model.
4. Using these results as context, describe the importance of selecting an appropriate date range for building a model.

**Project Data:**
WWL_NHS.csv attached contains a subset of the electronic patient record (EPR) data that are collected for each patient admitted into the hospital.

Definitions of ambiguous variables in the data set are shown below:

**Spell_episode_los** = the length of stay of an individual patient’s “spell” (A Hospital Provider Spell is the total continuous stay of a patient using a Hospital Bed)
**Admission** = entry time point into a hospital bed. Beginning of spell.
**Discharge** = exit time point out of hospital bed. End of spell.
**Readmission_flag_28_days** = Binary variable. Has a patient had a previous spell within 28 days. 1 = yes; 0 = no.
**Dementia_diagnosis_flag** = Binary variable. Patient has dementia. 1 = yes; 0 = no.
**Spell_primary_diagnosis** = primary diagnosis is the International Classification of Diseases (ICD) code used to identify the primary diagnosis. 9
**Spell_secondary_diagnosis** = secondary diagnosis is the International Classification of Diseases (ICD) code used to identify the secondary diagnosis.
**Spell_dominant_proc** = the primary procedure carried out to the patient.
**doctor_foster_comorbidity_score** = scoring system for assessing patient frailty.

**Additional Info:**
Organisation Name: NHS Wrightington, Wigan and Leigh
Main Contact: Dr Thomas Ingram, Head of Data Science
