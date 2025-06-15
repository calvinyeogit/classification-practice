# This is a personal practice mini-project.

It is inspired by the "Classification Practice Project" from the "Build Deep Learning Models with TensorFlow" Skill Path offered by Codecademy.

In this project, I predict whether a patient with heart failure stops living during the follow-up period, based on the following features:

1. `"age"`: Age
2. `"anaemia"`: Decrease of red blood cells or hemoglobin (boolean)
3. `"creatinine_phosphokinase"`: Level of the CPK enzyme in the blood (mcg/L)
4. `"diabetes"`: If the patient has diabetes (boolean)
5. `"ejection_fraction"`: Percentage of blood leaving the heart at each contraction (percentage)
6. `"high_blood_pressure"`: If the patient has hypertension (boolean)
7. `"platelets"`: Platelets in the blood (kiloplatelets/mL)
8. `"serum_creatinine"`: Level of serum creatinine in the blood (mg/dL)
9. `"serum_sodium"`: Level of serum sodium in the blood (mEq/L)
10. `"sex"`: Woman or man (binary)
11. `"smoking"`: If the patient smokes or not (boolean)
12. `"time"`: Follow-up period (days)

Since only 1 outcome has to be predicted for each patient, only 1 "label" exists for this model:

1. `"DEATH_EVENT"`: If the patient deceased during the follow-up period (boolean)

My personal best:
```
              precision    recall  f1-score   support

           0       0.87      0.87      0.87        39
           1       0.76      0.76      0.76        21

    accuracy                           0.83        60
   macro avg       0.82      0.82      0.82        60
weighted avg       0.83      0.83      0.83        60
```