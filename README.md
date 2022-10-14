# Credit_Risk_Analysis
A use of data preparation, statistical reasoning, and machine learning to analyze credit risk

## Overview of the analysis
The Purpose of this assisgmnet was to use different machine learning models to determine the best way to analyze Credit Risk predictions.

## Results
### Oversampling 

![Oversampling](/Images/Oversampling.JPG)

* Balanced accuracy score: 0.83
* Precision: 0.99 
* Recall: .84/.82

### SMOTE Oversampling 

![SMOTEOversampling](/Images/SMOTEOversampling.JPG)

* Balanced accuracy score: 0.84
* Precision: 0.99
* Recall: .87/.82

### Undersampling 

![Undersampling](/Images/Undersampling.JPG)

* Balanced accuracy score: 0.84
* Precision: 0.99
* Recall: .87/.88

### OverAndUnder 

![OverAndUnder](/Images/OverAndUnder.JPG)

* Balanced accuracy score: 0.82
* Precision: 0.99
* Recall: .86/.83

### Balanced Random Forest Classifier

![BRF](/Images/BRF.JPG)

* Balanced accuracy score: 0.68
* Precision: 1.00
* Recall: 1.0/.37

## Summary
Of these models, the best predictor seems to be the undersampling machine learning model. With all of these models having pretty similar balanced accuracy scores and precision, the undersampling methods higher recall average of .88 sets it apart from the pack. 
