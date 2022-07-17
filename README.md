# Credit_Risk_Analysis

## Overview

In this project we used Python and the Pandas library to prepare a dataset for a number of machine learning processes made possible by the imbalanced-learn and scikit-learn python packages. This is an example of supervised machine learning as we had a specific question we were looking to answer. In this case we using machine learning to predict credit risk. The dataset we utilized contained loan information from quarter 1 of 2019.

We ran six different machine learning processes once the data was in proper shape. The machine learning methods we used were:
- Naive Random Oversampling
- SMOTE Oversampling
- Cluster Centroid Undersampling
- SMOTEENN Sampling
- Balanced Random Forest Classifying
- Easy Ensemble Classifying

## Resources
Data Source: LoanStats_2019Q1.csv
Software: Python 3.9.12, Conda 4.13.0, Jupyter Notebook 6.4.8


## Results
### Naive Random Oversampling
![N Random Oversample 1](/images/RandomOS_1.png)
![N Random Oversample 2](/images/RandomOS_2.png)
![N Random Oversample 3](/images/RandomOS_3.png)
Balanced Accuracy Score: 66.6%
Precision Score:
    - High Risk: 1%
    - Low Risk: 100%
Recall
    - High Risk: 64%
    - Low Risk: 69%

### SMOTE Model
![SMOTE 1](/images/SMOTE_1.png)
![SMOTE 2](/images/SMOTE_2.png)
![SMOTE 3](/images/SMOTE_3.png)
Balanced Accuracy Score: 62.5%
Precision Score:
    - High Risk: 1%
    - Low Risk: 100%
Recall
    - High Risk: 61%
    - Low Risk: 62%


### Cluster Cewntroid Undersampling
![Undersample 1](/images/Under_1.png)
![Undersample 2](/images/Under_2.png)
![Undersample 3](/images/Under_3.png)
Balanced Accuracy Score: 62.5%
Precision Score:
    - High Risk: 1%
    - Low Risk: 100%
Recall
    - High Risk: 64%
    - Low Risk: 61%

### SMOTEENN Model (Combination Sampling)
![SMOTEENN 1](/images/Combo_1.png)
![SMOTEENN 2](/images/Combo_2.png)
![SMOTEENN 3](/images/Combo_3.png)
Balanced Accuracy Score: 61.9%
Precision Score:
    - High Risk: 1%
    - Low Risk: 100%
Recall
    - High Risk: 55%
    - Low Risk: 69%

### Balanced Random Forest Classifier Model
![BRFC 1](/images/brfc_1.png)
![BRFC 2](/images/brfc_2.png)
![BRFC 3](/images/brfc_3.png)

Balanced Accuracy Score: 78.7%
Precision Score:
    - High Risk: 4%
    - Low Risk: 100%
Recall
    - High Risk: 67%
    - Low Risk: 91%



### Easy Ensamble Classifying
![EEC 1](/images/eec_1.png)
![EEC 2](/images/eec_2.png)
![EEC 3](/images/eec_3.png)
Balanced Accuracy Score: 92.5%
Precision Score:
    - High Risk: 7%
    - Low Risk: 100%
Recall
    - High Risk: 91%
    - Low Risk: 94%




## Summary