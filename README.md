# Heart_Failure-_Prediction
A study to predict mortality by heart failure.

The dataset is 'Heart Failure Prediction' at the location: https://www.kaggle.com/andrewmvd/heart-failure-clinical-data

The dataset provided by the study contains 12 features which can be used to predict heart failure - an event associated with CVD which is the number 1 cause of death globally.

The study from which this dataset is derived claims that heart failure can be predicted from serum creatinine level and ejection fraction alone. Hence, these 2 will be major features of interest for the below analysis.

However, the study also includes features such as diabetes, anaemia etc. which are considered as major risk factors for CVD. Hence, this analysis will also try to derive insights regarding the significance of such factors and see if they play a role in predicting CVD as well.

In this analysis, Recall will be as important as Accuracy and more important than Precision. This is because it is more important to identify all patients who are at risk of heart failure even if it leads to a mis-identification of some patients (who are not at risk) as at risk of heart failure.
